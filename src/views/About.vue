<template>
  <div class="about">
    <h1>AUTHORS</h1>
    <li v-for="author in authors" v-bind:key="author">
      {{author.name}}
      <img alt="Vue logo" src= {{author.imag}}>
    </li>

  </div>
</template>

<script>
export default {
  data() {
    return {
      authors: [
        { name: "Sharmen Claire", imag: "../assets/digital.jpg"},
        { name: "Jane" },
        { name: "Jonathan" },
        { name: "Redgie" }
      ]
    };
  }
};
</script>
