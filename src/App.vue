<template>
  <div id="app">
    <div id="nav">
      <div>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>
body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

/* #nav {
  padding: 0 0 30px 0;
  background: url('./assets/images/navbg.jpg');
  background-size: center center;
} */

#nav > div {
  background: rgba(0,0,0, 1);
  margin: 0;
  padding: 20px 0;
  width: 100%;
}

#nav a {
  font-weight: bold;
  color: #fff;
}

#nav a.router-link-exact-active {
  color: #ff0000;
}
</style>
