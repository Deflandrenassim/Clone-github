<template>
  <div class="container">
    <h1>{{ hello }}</h1>
    <h2>
      Github est notre référence a tous les developpeurs. <br />
      C'est pour cela que j'ai voulut re faire la page principal <br> de github avec
      ma petite touche de personnalisation. <br />Passionné par le web j'aime
      reproduire les outils que <br> j'utilise au quotidien.
    </h2>

    <div class="information">
      <input type="text" class="search" placeholder="nassim.def@gmail.com" />
      <button class="lien-github">Lien de mon github </button>
    </div>

     <div class="images-p">
    <img class="imagesToy" src="@/assets/terre.png" alt="Toy Story "  />
      </div>
  </div>

</template>

<script>
export default {
  name: "World",
  data() {
    return {
      hello: "HELLO WORLD WELCOME, ",
      lienGit: "https://github.com/Deflandrenassim" // mon lien git hub pour le router plus tard 
    };
  },
};
</script>

<style scoped>
.container {
  margin-top: 10rem;
}
.h2 {
  font-size: 17px;
}
.information{
  margin-top: 3rem;
}
.search{
  height: 35px;
  width: 175px;
  border-radius: 10%;
  border: none;
}
.lien-github{
  background-color: #33a754;
  cursor:pointer;
  height: 35px;
  width: 175px;
  border: none;
  margin-left: 10px;
  color: white;
}
.lien-github:hover{
  background-color:#2a9e4b;
}
.images-p{
  position: absolute;
  top: 100px; left: 800px;
}
.imagesToy{
  height: 25rem;
  width: 29em;
}
</style>