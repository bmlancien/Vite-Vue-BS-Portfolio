<script>
import ButtonCta from "./components/Button-cta.vue";

export default {
  components: {
    ButtonCta,
  },
};
</script>

<template>
  <div id="app">
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
