<script>
import Button from './components/Button.vue';

export default {
  components: {
    Button
  }
}
</script>

<template>
  <div id="app">
    <Button />
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