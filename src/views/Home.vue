<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>Front-End Engineer</h1>

      <p class="subtxt">XXXXXX</p>
      <p class="subtxt">XXXXXX</p>
    </div>
    <div class="right-content img1">
      <button>
        <router-link to="/portfolio/one">My Work</router-link>
      </button>
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
    background: url('../assets/home.jpg');
  }
</style>

