<template>
  <div class="container">
    <h1>{{ hello }}</h1>
    <h2 class="txt">
      Github est notre référence a tous les developpeurs. <br />
      C'est pour cela que j'ai voulut re faire la page principal <br />
      de github avec ma petite touche de personnalisation. <br />Passionné par
      le web j'aime reproduire les outils que <br />
      j'utilise au quotidien.
    </h2>

    <div class="information">
      <input type="text" class="search" placeholder="nassim.def@gmail.com" />
      <button class="lien-github">Lien de mon github</button>
    </div>

    <div class="images-p">
      <img class="imagesToy" src="@/assets/github.png" alt="Toy Story " />
    </div>

    <div class="container-toy">
      <img class="toy-image" src="@/assets/toy.png" alt="Toy Story " />
    </div>
  </div>
</template>

<script>
export default {
  name: "World",
  data() {
    return {
      hello: "HELLO WORLD WELCOME, ",
      lienGit: "https://github.com/Deflandrenassim", // mon lien git hub pour le router plus tard
    };
  },
};
</script>

<style scoped>
.container {
  margin-top: 10rem;
}
.txt {
  font-size: 18px;
  color: #8193b2;
}
.information {
  margin-top: 3rem;
}
.search {
  height: 35px;
  width: 295px;
  border: none;
}
.lien-github {
  background-color: #33a754;
  cursor: pointer;
  height: 35px;
  width: 175px;
  border: none;
  margin-left: 10px;
  color: white;
}
.lien-github:hover {
  background-color: #2a9e4b;
}
.images-p {
  position: absolute;
  top: 80px;
  left: 680px;
}
.imagesToy {
  height: 33rem;
  width: 35em;
}
.container-toy{
  display: flex;
  align-content: flex-end;
  
}
.toy-image{
  height: 450px;
  width: 200px;
  position: absolute;
  top: 300px;
  left: 950px;
}
</style>