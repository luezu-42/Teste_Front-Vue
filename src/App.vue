<template>
  <div id="app">
    <Banner />
    <router-view></router-view>
  </div>
</template>

<script>
import Banner from "./components/Banner/Banner";

export default {
  name: "App",
  components: {
    Banner,
  },
};
</script>

<style src="./global.scss" lang="scss"/>
