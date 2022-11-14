<template>
  <img class="BomBa__logo" alt="Vue logo" src="./assets/logo.jpg" />
  <HelloWorld msg="Welcome to BomBa Software." />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
  },
};
</script>

<style lang="scss">
$c00: #efefef;
$c60: #909090;
$c30: #2c3e50;
$c10: #f18486;
body {
  background: $c60;
  color: $c00;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: $c30; */
  margin-top: 60px;
}
.BomBa__logo {
  padding: 5px;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 3px solid $c30;
  box-shadow: 0px 0px 20px $c10;
}
</style>
