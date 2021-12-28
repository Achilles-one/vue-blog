<template>
<div class="home">
    <el-table :data="tableData" border style="width: 100%">
        <!-- prop定义表格属性 -->
    <el-table-column prop="date" label="日期" width="180" />
    <el-table-column prop="name" label="姓名" width="180" />
    <el-table-column prop="address" label="地址" />
  </el-table>
  </div>
</template>

<script>


export default {
  
}
</script>
