<template>
  <div id="app">
    <MainHeader />
    <!-- <router-link to="/">Home</router-link> | -->
    <!-- <router-link to="/about">About</router-link> -->
    <router-view />
  </div>
</template>

<script>
import MainHeader from "@/components/MainHeader.vue";

export default {
  name: "App",
  components: {
    MainHeader,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300;600;800&display=swap");
#app {
}
</style>
