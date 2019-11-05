<template>
  <center class="imagess">
    <img :src="picture" />
    <h3>{{name}}</h3>
    <i>{{text}}</i>
  </center>
</template>
<script>
export default {
  props: {
    name: String,
    picture: String,
    text: String
  }
};
</script>
<style scoped>
img {
  width: 300px;
  max-width: 100%;
  height: 320px !important;
  overflow: hidden;
}
.imagess {
  margin-top: 3%;
}

</style>