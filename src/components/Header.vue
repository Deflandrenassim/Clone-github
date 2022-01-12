<template>
  <div class="container">
      <div class="h-droit">
        <nav class="navbar">
          <ul>
            <li> {{ home }}</li>
            <li> {{ pr }}</li>
            <li> {{ exp }}</li>
          </ul>
        </nav>
      </div>
      <div class="h-gauche">
        <input type="text" class="search" placeholder="Recherche github" />
        <button class="connexion">Connexion</button>
        <button class="inscription">Inscription</button>
      </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      exp: "Expérience",
      pr : "Projet",
      home : "Home"
}
  }

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  margin: 0 100px;
}
.center {
  display: flex;
  flex-direction: row;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.h-gauche{
  display: flex;
  align-items: center;
  justify-content: flex-end;
}
</style>
