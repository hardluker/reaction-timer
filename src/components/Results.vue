<template>
  <p>Reaction Time: {{ score }}</p>
</template>

<script>
export default {
  props: ['score'],
  data() {
    return {
      rank: null
    };
  }
};
</script>

<style></style>
