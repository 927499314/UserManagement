<template>
  <div id="app">
    <Header></Header>
    <router-view></router-view>
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "app",
  components: {
    Header,
  }
};
</script>


<style>
#app {
  margin: 0;
  padding: 0;
}
</style>
