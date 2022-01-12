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
        <input type="text" class="search" placeholder="Recherche.." />
        <button class="connexion">Connexion</button>
        <button class="inscription">Inscription</button>
      </div>
<h3> {{ dateBuilder }}</h3>
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
  },
  methods: {
    dateBuilder(){
      let now = new Date();
      let annee   = now.getFullYear();
      let mois    = now.getMonth() + 1;
      let jour    = now.getDate();
      let heure   = now.getHours();
      let minute  = now.getMinutes();
      let seconde = now.getSeconds();
    
      return `${annee} ${mois} ${jour} ${heure} ${minute} ${seconde}`;
    }
  }
  

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  
  
}
.center {
  display: flex;
  flex-direction: row;
}
.navbar {
  color: white;
  cursor: pointer;
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
  color: white;
  
}
.search {
  
  margin : 10px;
  padding: 11px;
}
.connexion {
  border: none;
  outline: 0px;
  border-radius: 2rem;
  background: transparent;
  cursor: pointer;
  color: white;
  
}
.connexion:hover, 
.inscription:hover{
  transition : 1.6s;
  color: rgb(248, 196, 196);
  font-size: 20px;
}
.inscription {
  cursor: pointer;
  margin : 10px;
  color: white;
  background: transparent;
  border: 1.5px;
}
</style>
