<template>
  <header class="header">
    <ul class="nav-items">
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/users">Users</nuxt-link></li>
    </ul>
  </header>
</template>
<style scoped>
.header{ 
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: lightgray; 
}
.nav-items {
  list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 80%;
}
</style>
