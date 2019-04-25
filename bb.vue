<template>
  <div>
    <el-main>
      <el-table :data="tableData">
        <el-table-column prop="date" label="123" width="140">
        </el-table-column>
        <el-table-column prop="name" label="456" width="120">
        </el-table-column>
        <el-table-column prop="address" label="789">
        </el-table-column>
      </el-table>
    </el-main>
  </div>

</template>

<script>
  export default {
    data() {
      const item = {
        date: '2016-05-02',
        name: '张三',
        address: '789'
      };
      return {
        tableData: Array(20).fill(item)
      }
    }
  };
</script>

<style scoped>

</style>
