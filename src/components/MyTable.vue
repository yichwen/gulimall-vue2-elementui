<template>
  <el-table :data="tableData">
    <el-table-column prop="date" label="Date" width="140"> </el-table-column>
    <el-table-column prop="name" label="Name" width="120"> </el-table-column>
    <el-table-column prop="address" label="Address"> </el-table-column>
  </el-table>
</template>

<script>
export default {
  name: "MyTable",
  data() {
    const item = {
      date: "2016-05-02",
      name: "Tom",
      address: "No. 189, Grove St, Los Angeles",
    };
    return {
      tableData: Array(20).fill(item),
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
