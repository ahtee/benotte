<template>
  <img :src="src" :alt="alt" />
</template>

<script>
export default {
  props: {
    alt: String,
    src: String,
  },
};
</script>

<style scoped></style>
