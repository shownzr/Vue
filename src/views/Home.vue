<template>
  <div>
    <el-table :data="tableData" border style="width: 100%">
      <el-table-column prop="date" label="Date"  />
      <el-table-column prop="name" label="Name"  />
      <el-table-column prop="address" label="Address" />
    </el-table>
  </div>
</template>

<script>
export default {
  name:'Home',
  components:{

  },
  data(){
    return{
      tabledata:[]
    }
  }
}


</script>
