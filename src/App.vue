<script setup lang="ts">

</script>

<template>
  <ul class="guider">
    <li><a href="#home">主页</a></li>
    <li><a href="#news">新闻</a></li>
    <li><a href="#contact">联系</a></li>
    <li><a href="#about">关于</a></li>
  </ul>
  <div class="back">
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <img src="./assets/logo.png" class="logo" alt="logo" /><br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
  scale: 4;
  text-align: center;
  left: 50%;
  right: 0;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #ffdd00);
}
.guider {
  list-style-type: none;
  position: fixed;
}

.guider li {
  float: right;
  margin: 20px;
  height: 40px;
}

@media screen and (max-width: 500px) {
  .logo {
    scale: 1.6
  }
  .guider {
    margin-left: 0
  }
  .guider li {
    float: inline-start;
  }
}
</style>
