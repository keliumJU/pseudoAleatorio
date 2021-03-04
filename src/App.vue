<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/cuadrados-medios">Cuadrados Medios</router-link> |
<<<<<<< HEAD
      <router-link to="/lineal-algo">Lineal Algoritmo</router-link> | 
=======
      <router-link to="/multiplicador-constante">MultiplicadorConstante</router-link> |
>>>>>>> 52e7faddf0f92fedc844401034c81ee6079d4f21
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
