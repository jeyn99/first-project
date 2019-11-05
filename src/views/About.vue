<template>
  <div class="about">
    <h1>AUTHORS</h1>
    <b-container fluid>
      <b-row class="justify-content-md-center">
        <b-col><Member v-bind:picture="require('../assets/red.png')" v-bind:name="'Redgie Gravador'"></Member></b-col>
        <b-col><Member v-bind:picture="require('../assets/jonathan.jpg')" v-bind:name="'Jonathan Rivas'"></Member></b-col>
        <b-col><Member v-bind:picture="require('../assets/sharmen.jpg')" v-bind:name="'Sharmen Avila'"></Member></b-col>
        <b-col><Member v-bind:picture="require('../assets/jane.jpg')" v-bind:name="'Jane Repollo'"></Member></b-col>
      </b-row>
    </b-container>   
  </div>
</template>

<script>
import Member from "@/components/members.vue";

export default {
  name: "about",
  components: {
    Member
  }
};
</script>
<style scoped>

.about {
  margin: 5%;
}

</style>