<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
// import { getData } from "./api/index";
export default {
  data() {
    return {};
  },
  async created() {},
};
</script>

<style lang="less">
// 清除浏览器默认样式
@import "../src/assets/reset.css";
html,
body {
  height: 100%;
  #app {
    height: 100%;
  }
  .container {
    height: 100%;
  }
}
</style>
