<template>
  <div id="app" class="container mx-auto">
    <div class="w-full my-8">
      <button @click="selectedComponent = 'Quote'"  class="py-2 px-4 rounded border border-blue bg-blue hover:bg-blue-dark mr-4 text-white">Цитата</button>
      <button @click="selectedComponent = 'Author'" class="py-2 px-4 rounded border border-blue bg-blue hover:bg-blue-dark mr-4 text-white">Автор</button>
      <button @click="selectedComponent = 'New'"    class="py-2 px-4 rounded border border-blue bg-blue hover:bg-blue-dark mr-4 text-white">Новая</button>
      <hr class="border border-grey">
      <div class="py-8">
        {{ selectedComponent }}
      </div>
      <!-- <Quote>
        <h2 slot="title">{{ quoteTitle }}</h2>
        <p>Супер цитата</p>
        <p>Продолжение</p>
      </Quote> -->
    </div>

  </div>
</template>

<script>
import Quote from './components/Quote.vue'
import Author from './components/Author.vue'
import New from './components/New.vue'
export default {
  name: 'app',
  data() {
    return {
      quoteTitle: 'Умная цитата!',
      selectedComponent: 'Quote'
    }
  },
  components: {
    Quote,
    Author,
    New
  }
}
</script>

<style>

</style>
