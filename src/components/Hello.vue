<template>
  <div>
    <h1>Hello, {{ name }}</h1>
    <el-radio v-model="radio" label="1">Selection</el-radio>
    <el-radio v-model="radio" label="2">Selection</el-radio>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  data() {
    return {
      name: 'John Doe',
      radio: '2'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
