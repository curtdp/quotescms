<template>
  <div class="border border-gray p-8 shadow-lg text-center text-5xl font-sans font-light">
    <div class="border border-gray mb-8 shadow-md p-4">
      <slot name="title"></slot>
    </div>
    <div class="border border-gray shadow-md p-4">
      <slot></slot>
    </div>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
  h2 {
    color: red;
  }
</style>