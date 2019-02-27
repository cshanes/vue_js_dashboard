<template>
  <div>
    <p>UV Index: {{ uvindex }}</p>
  </div>
</template>

<script>

  export default {
    props: ["highlights"],
    data () {
      return {
        uvindex: this.highlights.uvIndex.toString()
      }
    },
    methods: {

    },
    computed: {

    },
  }
</script>

<style>

</style>
