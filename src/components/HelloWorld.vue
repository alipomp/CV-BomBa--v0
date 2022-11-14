<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>he I'm hussein abdo </h3>
    <p>My job is a</p>
    <h4 style="display: inline;">full stack web developer</h4>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
