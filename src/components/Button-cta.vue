<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<template>
  <button @click="count++" class="btn btn-primary btn-lg">
    You clicked me {{ count }} times.
  </button>
</template>
