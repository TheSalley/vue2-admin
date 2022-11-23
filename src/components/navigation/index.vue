<template>
  <el-row type="flex" justify="space-between">
    <el-col :span="6">
      <div class="grid-content">
        <img src="../../assets/logo.png" alt="" />
      </div>
    </el-col>
    <el-col :span="6">
      <div class="grid-content"></div>
    </el-col>
  </el-row>
</template>
<script>
export default {};
</script>

<style lang="less" scoped>
.el-row {
  margin-bottom: 20px;
  &:last-child {
    margin-bottom: 0;
  }
  background: #1890ff;
  height: 60px;
  img {
    width: 50px;
    height: 50px;
  }
}
</style>
