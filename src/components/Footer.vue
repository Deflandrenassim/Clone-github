<template>
  <div>

      <hr  class="hr"/>
     
    <div class="container">
      <img class="image" src="@/assets/github.png" alt=" git hub "  />
       <img class="image" src="@/assets/mail.png" alt=" mail" />
      <img class="image" src="@/assets/linkedin.png" alt=" linkedin" />
    
    </div>

  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.hr{
    margin: 8rem;
    opacity: 0.4;
    color: rgb(247, 218, 218);
}
.container{
    display: flex;
    justify-content: center;
    justify-content: space-around;
    margin: 5em;
}
.image{
    cursor: pointer;
    height: 40px;
    width: 30px;
}

</style>