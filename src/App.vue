<template>
  <div class="home">
    <Header />
    <World />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import World from './components/World.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Header,
    World,
    Footer,
  }
}
</script>

<style>
body{
  font-family: Arial, Helvetica, sans-serif;
  color: white;
  background: rgb(16,45,177);
  background: linear-gradient(90deg, rgba(16,45,177,1) 0%, rgba(186,0,255,1) 100%);
  margin: 0 100px;
}
</style>
