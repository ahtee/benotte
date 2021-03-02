<template>
  <div id="app">
    <Logo :alt="logoAltText" :src="logo" />
    <Intro :title="title" :headline="headline" />
  </div>
</template>

<script>
import Intro from "./components/Intro.vue";
import Logo from "./components/Logo.vue";

import face from "./assets/face.jpg";

export default {
  components: {
    Intro,
    Logo,
  },
  data() {
    return {
      logoAltText: "Ben Otte",
      logo: face,
      title: "Ben Otte",
      headline: "Software Engineer, Cloud certified",
    };
  },
};
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2a4b45;
  margin-top: 60px;
}
</style>
