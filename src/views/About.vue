<template>
  <div class="about">
    <h1>AUTHORS</h1>
    <b-container fluid>
      <b-row>
        <b-card deck v-for="author in authors" v-bind:key="author" style="width: 25%">
          <b-col>
            <b-card bg-variant="info" text-variant="white" header="Profile" class="text-center">
              <Member v-bind:picture="author.imag" v-bind:name="author.name"></Member>
              <b-card-text>{{author.text}}</b-card-text>
            </b-card>
          </b-col>
        </b-card>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Member from "@/components/members.vue";

export default {
  data() {
    return {
      authors: [
        {
          name: "Jonathan Rivas",
          imag: require("@/assets/jonathan.jpg"),
          text: "Full Stack Developer"
        },
        {
          name: "Redgie Gravador",
          imag: require("@/assets/red.png"),
          text: "Full Stack Developer"
        },
        {
          name: "Sharmen Claire Avila",
          imag: require("@/assets/sharmen.jpg"),
          text: "Full Stack Developer"
        },
        {
          name: "Jane Repollo",
          imag: require("@/assets/jane.jpg"),
          text: "Web Devloper"
        }
      ]
    };
  },
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