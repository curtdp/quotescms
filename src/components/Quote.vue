<template>
  <div class="border border-gray p-8 shadow-lg text-center text-5xl font-sans font-light">
    <p>{{ quote }}</p>
  </div>
</template>

<script>
  export default {
    props: ['quote']
  }
</script>

<style scoped>

</style>