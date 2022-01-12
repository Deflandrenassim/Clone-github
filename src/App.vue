<template>
  <div class="home">
    <Header />
  </div>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
body{
  background: rgb(16,45,177);
background: linear-gradient(90deg, rgba(16,45,177,1) 0%, rgba(186,0,255,1) 100%);
}
</style>
