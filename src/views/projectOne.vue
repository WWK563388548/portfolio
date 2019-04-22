<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>Projects Of Front-End</h1>

      <p class="subtxt">XXXXXX</p>
      <p class="subtxt">XXXXXX</p>

      <router-link to='/portfolio/two'>
        <img src="../assets/arrow-down.svg" class="arrow arrow-down" />
      </router-link>
    </div>
    <div class="right-content img2">
    </div>
  </div>
</template>

<script>

export default {
  name: "PortfolioOne",
  components: {
    
  }
};
</script>

<style lang="scss" scoped>
    $page_color: #625B7E;

    h1 {
        color: $page_color !important;
    }

    .img2 {
        background: url("../assets/home.jpg");
        background-size: cover;
        background-position: 50%;

        img {
            widows: 50%;
        }
    }
</style>