<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>About me</h1>
      <p class="subtxt">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
      <button class="about-button">
        <router-link to="/portfolio/one">Look at my work</router-link>
      </button>
      <button class="about-button-resume">
        <router-link to="#">My Resume</router-link>
      </button>
    </div>
    <div class="right-content about-img">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur blanditiis inventore sit modi nulla praesentium repudiandae obcaecati possimus quasi assumenda alias deserunt dolorem cupiditate expedita asperiores unde, iure amet? Ipsa.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur blanditiis inventore sit modi nulla praesentium repudiandae obcaecati possimus quasi assumenda alias deserunt dolorem cupiditate expedita asperiores unde, iure amet? Ipsa.</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>

  .left-content {
    background-color: #ffe476;
  }

  .right-content {
    background: #fff;
    padding: 50px;
    margin-top: 80px;
    display: block;
  }

  .subtxt {
    font-size: 1.5em;
    margin-top: 30px;
  }

  .about-button {
    background: none;
    padding: 15px 20px;
    outline: 0;
    border: 1px solid #017FAF;
    color: #017FAF;
    font-size: 1.5em;
    margin-top: 100px;
    text-transform: uppercase;
    font-family: 'Montserrat';
    border-radius: 0;
    cursor: pointer;
    a {
      color: #017FAF;
    }
  }

  .about-button-resume {
    background: none;
    padding: 15px 20px;
    outline: 0;
    border: 1px solid #017FAF;
    color: #017FAF;
    font-size: 1.5em;
    margin-top: 10px;
    text-transform: uppercase;
    font-family: 'Montserrat';
    border-radius: 0;
    cursor: pointer;
    a {
      color: #017FAF;
    }
  }
</style>
