<template>
  <div class="container">
    <h1> {{ hello }} <br> {{ perso }}</h1>
    <h2> Github est notre référence a tous les developpeurs c'est pour cela que j'ai voulut re faire la page 
      principal de github avec ma petite touche de personnalisation
    </h2>
  
  </div>
</template>

<script>
export default {
  name: "World",
  data() {
    return {
      hello: 'HELLO WORLD WELCOME, ',
      perso: 'Dans mon github personnalisé '
    };
    
  },
};
</script>

<style scoped>
.container{
  margin-top: 10rem;
}
h1 hello{
  text-align: center;
}


</style>