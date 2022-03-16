<template>
  <div style="height: 50px;line-height: 50px;border-bottom: 1px solid #cccccc;display: flex;position: relative">
    <div style="width: 200px;padding-left: 10px;font-weight: bolder;font-size:20px;font-family: 黑体;color: #409eff">后台管理系统</div>
    <div style="flex: 1"></div>
    <div style="width:100px">
      <el-dropdown style="position: absolute;top:10px;right: 20px">
        <el-button type="primary" >
          寿振仁<el-icon class="el-icon--right"><arrow-down /></el-icon>
        </el-button>
        <template #dropdown>
          <el-dropdown-menu>
            <el-dropdown-item>个人中心</el-dropdown-item>
            <el-dropdown-item>退出系统</el-dropdown-item>
          </el-dropdown-menu>
        </template>
      </el-dropdown>
    </div>
  </div>
</template>

<script>
import {ArrowDown} from '@element-plus/icons-vue'
export default {
  name: "Header",
  components:{
    ArrowDown
  }
}

</script>

<style scoped>

</style>