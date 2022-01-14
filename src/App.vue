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
    Footer
}
}
</script>

<style>
body{
  font-family: Arial, Helvetica, sans-serif;
  color: white;
  background: #040e22;
  margin: 0 100px;
}

</style>
