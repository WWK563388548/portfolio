<template>
  <div class="two main-content">
    <div class="left-content slideUp">

        <router-link to='/portfolio/one'>
            <img src="../assets/arrow-up.svg" class="arrow arrow-up" />
        </router-link>

        <h1>Mobile App Projects</h1>

        <p class="subtxt">XXXXXX</p>
        <p class="subtxt">XXXXXX</p>

        <router-link to='/portfolio/three'>
            <img src="../assets/arrow-down.svg" class="arrow arrow-down" />
        </router-link>
    </div>
    <div class="right-content img2">
    </div>
  </div>
</template>

<script>

export default {
  name: "PortfolioTwo",
  components: {
    
  }
};
</script>

<style lang="scss" scoped>
    $page_color: #48b886;

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