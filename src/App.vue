<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
*,
*:after,
*:before {
  box-sizing: border-box;
}
html,
body {
  min-height: 100%;
  margin: 0px;

  padding: 0px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  background-color: rgb(30, 29, 42);
  
background: linear-gradient(167deg, rgb(30, 29, 42) 0%, rgb(38, 35, 70) 54%, rgb(77, 73, 110) 100%);
  position: relative;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
