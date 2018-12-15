<template>
  <div id="app">
    
      <nav class="navbar navbar-expand navbar-dark bg-dark">
          <div class="nav navbar-nav">
              <router-link to="/" class="nav-item nav-link active">Home </router-link>
              <router-link to="/about" class="nav-item nav-link">About</router-link>
              <router-link to="/employees" class="nav-item nav-link">employees</router-link>
          </div>
      </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #a3a3a3;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #d10d0d;
}

#nav a.router-link-exact-active {
  color: #0c0fd8;
}
</style>