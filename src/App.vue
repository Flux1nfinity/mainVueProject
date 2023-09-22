<script setup lang="ts">
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="32" height="32" />
    <a href="#">About</a>
    <a href="#">Catalog</a>
    <a href="#">Community</a>
    <a href="#">Support</a>
    <a href="#">Donate</a>
    <img alt="user logo" class="user" src="./assets/user-solid.svg" width="24" height="24" />
  </header>
</template>

<style scoped>

.logo {
  display: block;
  margin: 0;
} 

header {
  width: 100vw;
  height: 3rem;
  background-color: #181818;
  display: flex;
  box-shadow: 0 10px 6px -6px #292929;
  overflow: hidden;
}
header a{
  padding: 0.55rem 2rem;
  font-family: calibri;
  font-size: 18px;
  font-weight: lighter;
}

.logo {
  align-self: center;
  margin: 0 5rem 0 5rem;
}
.user {
  transform: translateX(50vw);
  align-self: center;
}
</style>
