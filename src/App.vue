<template>
  <div id="app" class="container mx-auto">
    <div class="w-full my-8">
      <Quote>
        <h2>{{ quoteTitle }}</h2>
        <p>Супер цитата</p>
      </Quote>
    </div>

  </div>
</template>

<script>
import Quote from './components/Quote.vue'
export default {
  name: 'app',
  data() {
    return {
      quoteTitle: 'Умная цитата!'
    }
  },
  components: {
    Quote
  }
}
</script>

<style>

</style>
