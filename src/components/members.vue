<template>
  <center class="imagess">
    <img :src="picture" />
    <h3>{{name}}</h3>
  </center>
</template>
<script>
export default {
  props: {
    name: String,
    picture: String
  }
};
</script>
<style scoped>
img {
  width: 300px;
  height: 320px !important;
}
.imagess {
  margin-top: 5%;
}

</style>