<template>
  <el-select size="small" v-model="type" clearable placeholder="请选择类型">
    <el-option value="1" label="1"></el-option>
    <el-option value="2" label="2"></el-option>
  </el-select>
</template>

<script setup>
import { ref } from "vue";
import { ElSelect, ElOption } from "element-plus";
const type = ref("1");
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
