<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <InboxScreen />
  </div>
</template>

<script>
import InboxScreen from './components/InboxScreen.vue'

export default {
  name: "App",
  components: {
    InboxScreen
  }
};
</script>

<style>
@import "./index.css";
</style>
