<template>
  <styled-header>
    <styled-title>Internet</styled-title>
    <styled-title>Fixo</styled-title>
    <styled-title>Tv</styled-title>
    <styled-title>Carrinho</styled-title>
  </styled-header>
  
</template>

<script>
import { StyledHeader, StyledTitle } from "./Header.style";

export default {
  name: "Header",
  components: {
    StyledHeader,
    StyledTitle
  },
  props: {
    msg: String,
  },
};
</script>

