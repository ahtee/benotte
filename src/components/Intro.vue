<template>
  <div class="intro-section">
    <h1>{{ title }}</h1>
    <h2>{{ headline }}</h2>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    headline: String,
  },
};
</script>
