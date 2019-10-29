<template>
  <div class="home">
    <img alt="badgebook logo" src="../assets/logo.png">
    <HelloWorld msg="Badgebook"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>


