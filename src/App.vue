<template>
  <div id="app">
    <header-2 />
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import header2 from '@/components/header.vue'

export default {
  name: 'app',
  components: {
    header2
  }
}
</script>


<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  letter-spacing: 5px
}

#nav {
  font-size: 20px;
}

#nav a {
  font-weight: bold;
  color: white;
}

#nav a.router-link-exact-active {
  color: wheat;
}
</style>
