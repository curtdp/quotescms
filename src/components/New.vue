<template>
  <div class="border border-gray p-8 shadow-lg text-center text-5xl font-sans font-light">
    <h3 class="mb-8">Новая цитата</h3>
    <button @click="counter++" class="py-2 px-4 rounded border border-blue bg-blue hover:bg-blue-dark mr-4 text-white">Увеличить!</button>
    <p class="mt-4">{{ counter }}</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        counter: 0
      }
    },
    destroyed() {
      console.log('New component destroyed!')
    },
    activated() {
      console.log('New component activated!')
    },
    deactivated() {
      console.log('New component deactivated!')
    }
  }
</script>

<style scoped>

</style>