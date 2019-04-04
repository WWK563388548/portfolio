<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>Project One</h1>

      <p class="subtxt">XXXXXX</p>
      <p class="subtxt">XXXXXX</p>

      <router-link to='/portfolio/two'>
        <img src="../assets/arrow-down.svg" class="arrow arrow-down" />
      </router-link>
    </div>
    <div class="right-content img2">
      <img src="" />
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
        background: $page_color;
        img {
            width: 50%;
        }
    }
</style>