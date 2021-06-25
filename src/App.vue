<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <TaskList/>
  </div>
</template>

<script>
import TaskList from './components/TaskList.vue';

export default {
  name: "App",
  components: {
    TaskList
  }
};
</script>

<style>
@import "./index.css";
</style>
