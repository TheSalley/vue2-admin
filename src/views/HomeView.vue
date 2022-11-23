<template>
  <div class="container">
    <el-container>
      <el-header>
        <Navigation></Navigation>
      </el-header>
      <el-container>
        <el-aside width="200px">
          <asideMenu></asideMenu>
        </el-aside>
        <el-main>
          <Main></Main>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import Navigation from "../components/navigation";
import asideMenu from "../components/aside-menu";
import Main from "../components/main";
export default {
  name: "HomeView",
  components: {
    Navigation,
    asideMenu,
    Main,
  },
};
</script>

<style lang="less" scoped>
.container {
  .el-container {
    height: 100%;
    .el-header {
      padding: 0;
    }
    .el-aside {
      height: 100%;
      border-right: 1px solid #e6e6e6;
    }
  }
}
</style>
