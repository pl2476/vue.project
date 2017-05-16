<template>
  <div class="header">
    <el-row :gutter="10">
      <el-col :xs="8" :sm="6" :md="4" :lg="3">
        <div class="grid-content bg-purple">
          <h4>main</h4>
        </div>
      </el-col>
      <el-col :xs="4" :sm="6" :md="8" :lg="9">
        <div class="grid-content bg-purple-light">hello</div>
      </el-col>
      <el-col :xs="4" :sm="6" :md="8" :lg="9">
        <div class="grid-content bg-purple"></div>
      </el-col>
      <el-col :xs="8" :sm="6" :md="4" :lg="3">
        <div class="grid-content bg-purple-light"></div>
      </el-col>
    </el-row>
  </div>
</template>
<style>
.el-col {
  border-radius: 4px;
}

.bg-purple-dark {
  background: #99a9bf;
}

.bg-purple {
  background: #d3dce6;
}

.bg-purple-light {
  background: #e5e9f2;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
</style>
<script>
export default {
  name: 'head'
}
</script>
