<template>
  <div class="home">
    <img alt="badgebook logo" src="../assets/logo.png">
    <HelloWorld msg="Badgebook"/>
    <p>We propose a system called Badgebook. Badgebook is a micro-credentialing web application that offers a user to list all his digital certificates in one repository thus provide a professional development units portfolio. This digital certificates, called badge are valid since the organization themselves have issued it and can be easily verified. A user can register and get shareable link of their profile that shows their badge. On the other side organizations when conducting activities like seminars, missions, and workshops can give certificates in a more hassle-free and resources saving manner through digital certificates. This uses badges that represents a way of acknowledging achievements or skill acquisition. Only the organization can add a badge.
</p>
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
<style scoped>
img {
  margin-top: 4%
}
</style>


