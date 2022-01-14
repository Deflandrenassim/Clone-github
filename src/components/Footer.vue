<template>
  <div>
    <hr />
    <div class="container">
      <img class="image" src="@/assets/github.png" alt=" git hub " />
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
.container{
    display: flex;
    justify-content: center;
    justify-content: space-around;
    cursor: pointer;
}
.image{
    height: 40px;
    width: 30px;
}
</style>