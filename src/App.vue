<script>
import ButtonCta from "./components/Button-cta.vue";
import Header from "./components/Header.vue";

export default {
  components: {
    ButtonCta,
    Header
  },
};
</script>

<template>
  <div id="app">
    <Header />
    <ButtonCta />
  </div>
</template>

<style lang="scss">
h1 {
  color: green;

  &:hover {
    color: greenyellow;
  }
}
</style>
