<script setup lang="ts">

</script>

<template>
  <div class="back">
    wwww
    <!-- <img src="./assets/logo.png" class="logo" alt="logo" /><br /> -->
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
  scale: 4
}

.logo:hover {
  filter: drop-shadow(0 0 2em #8ff666aa);
}

.back {
  background-image: url('./background.png');
  margin: 0;
  background-size: 100%, 100%;
  background-attachment: fixed;
}
</style>
