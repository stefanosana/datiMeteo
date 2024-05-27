<template>
  <nav>
    <router-link to="/">Temperature</router-link> |
    <router-link to="/about">Precipitazioni</router-link> | 
    <router-link to="/città">Città</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #00434f;
  padding: 10px;
  z-index: 999;
  
}

nav a {
  font-weight: bold;
  color: #ffffff;
  font-size: large;
}
  


nav a.router-link-exact-active {
  color: #42b983;
}
</style>
