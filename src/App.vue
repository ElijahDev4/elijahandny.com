<template>
  <div id="app">
    <!-- Component Must be written here otherwise error ex: ( <Home msg="Welcome to Your Vue-Flask-Tailwind App" /> ) -->
    <MainHeader />
    <MainBodySkills />
    <MainBody />
    <MainBodyCards />
    <MainFooter />
  </div>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
import MainBodySkills from "./components/MainBodySkills.vue";
import MainBody from "./components/MainBody.vue";
import MainBodyCards from "./components/MainBodyCards.vue";
import MainFooter from "./components/MainFooter.vue";

export default {
  name: "App",
  components: {
    MainHeader,
    MainBodySkills,
    MainBody,
    MainBodyCards,
    MainFooter
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Open+Sans&display=swap");
body {
  font-family: "Open Sans", sans-serif;
}
</style>
