<template>
  <div id="app" class="container mx-auto">
    <div class="w-full my-8">
      <Quote quote="Очень классная цитата!"></Quote>
      <h2>Цитата</h2>
      <p>Супер цитата</p>
    </div>

  </div>
</template>

<script>
import Quote from './components/Quote.vue'
export default {
  name: 'app',
  components: {
    Quote
  }
}
</script>

<style>

</style>
