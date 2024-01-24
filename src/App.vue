<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> 
      <router-link to="/about">About</router-link>
      <router-link to="/models">Models</router-link> <!-- Corrected link -->
      <router-link to="/cart">Cart</router-link> <!-- Corrected link -->
      <router-link to="/admin">Admin</router-link> <!-- Corrected link -->
      <router-link to="/contact">Contact Us</router-link> <!-- Corrected link -->
    </nav>
    <router-view/>
  </div>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-image: url('~@/assets/2010s-2020.gif'); /* Adjusted path */
  background-size: cover; /* Adjusted size property */
  height: 100vh;
  width: 100%;
}

nav {
  padding: 30px;
  display: flex;
  gap: 30px;
  align-content: center;
  justify-content: center;
  text-decoration: none;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
