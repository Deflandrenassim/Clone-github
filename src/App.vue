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
background: rgb(4,14,34);
background: linear-gradient(135deg, rgba(4,14,34,1) 83%, rgba(68,31,71,1) 98%);
  margin: 0 100px;
}

</style>
