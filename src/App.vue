<template>
  <Header />
</template>

<script>
import Header from "./components/Header/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
  methods: {
    onClick() {
      console.log("click");
    },
  },
};
</script>

<style>
#app, *, body{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
  background-image: url("./assets/logo.jpg");
}
</style>