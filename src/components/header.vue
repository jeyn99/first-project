<template>
  <div id="nav">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand router-link to="/">Badgebook</b-navbar-brand>
      <b-navbar-nav  class="ml-auto">
        <b-nav-item router-link to="/">Home</b-nav-item>
        <b-nav-item router-link to="/about">About</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "head"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
#nav a {
  color: white;
}

#nav a.router-link-exact-active {
  color: red;
}
</style>
