<template>

  <body>

    

      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
    
      <router-view/>
    
    
    
  </body>



  
</template>

<style>

* {
  margin: 0;
  padding: 0;
}

#app {
  font-family: courier;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  background-image: url('../src/assets/background-trans-large.png');
  background-size: 1200px auto;
  background-color: rgb(42, 88, 134);
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
