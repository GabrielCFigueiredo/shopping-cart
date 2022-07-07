<template>
  <styled-header>{{ msg }}</styled-header>
</template>

<script>
import { StyledHeader } from "./Header.style";

export default {
  name: "Header",
  components: {
    StyledHeader,
  },
  props: {
    msg: String,
  },
};
</script>

<style>
</style>