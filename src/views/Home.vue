<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>Front-End Engineer</h1>

      <p class="subtxt">XXXXXX</p>
      <p class="subtxt">XXXXXX</p>
    </div>
    <div class="right-content img1">
      <div class="default-button">
        <router-link to="/portfolio/one">Browse Work</router-link>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "home",
  components: {
    
  }
};
</script>

<style scoped>
  .img1 {
    background: linear-gradient(to bottom, rgba(0, 0, 0, 0.7), transparent), url('../assets/new_background.jpg');
    background-size: cover;
    background-position: 50%;
  }
</style>

