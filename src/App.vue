<template>
  <div id="app">
    <Profile />
  </div>
</template>

<script>
import Profile from "./components/Profile.vue";

export default {
  name: "App",
  components: {
    Profile,
  },
};
</script>

<style lang="less">
body {
  padding: 0;
  margin: 0;


}

#app {
}
</style>
