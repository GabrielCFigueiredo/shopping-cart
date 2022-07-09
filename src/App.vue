<template>
  <Header />
  <h1>Assine a melhor internet de Fibra Óptica</h1>
  <styled-wrapper>
    <Card />
    <Card />
    <Card />
    <Card />
  </styled-wrapper>
</template>

<script>
import Header from "./components/Header/Header.vue";
import Card from "./components/Card/Card.vue";
import { StyledWrapper } from "./App.style.js"

export default {
  name: "App",
  components: {
    Header,
    Card,
    StyledWrapper
  },
  methods: {
    onClick() {
      console.log("click");
    },
  },
};
</script>

<style>
#app,
*,
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
  background-image: url("./assets/logo.jpg");
}
</style>
