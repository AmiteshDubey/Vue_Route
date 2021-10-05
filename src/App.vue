<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/project">Project</router-link> |
    <router-link to="/service">Service</router-link> |
    <router-link to="/contact">Contact</router-link> |
  </div>
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

#nav {
  font-size: 40px;
  padding: 30px;
  list-style-type: none;
  margin: 0;
  overflow: hidden;
  background-color: #333;
}

#nav a {
 /* display: block; */
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;

}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
