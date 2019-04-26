<template>
  <div class="three main-content">
    <div class="left-content slideUp">

        <router-link to='/portfolio/two'>
            <img src="../assets/arrow-up.svg" class="arrow arrow-up" />
        </router-link>

        <h1>Server-Side Projects</h1>

        <p class="subtxt">XXXXXX</p>
        <p class="subtxt">XXXXXX</p>

    </div>
    <div class="right-content img2">
    </div>
  </div>
</template>

<script>

export default {
  name: "PortfolioThree",
  components: {
    
  }
};
</script>

<style lang="scss" scoped>
    $page_color: #5487a8;

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