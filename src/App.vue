<template>
  <div class="app">
    <el-row justify="center" style="margin-top:40px">
      <el-col :span="12">
        <div style="text-align:center">
          <h1>Vue 3 + Element Plus + TypeScript</h1>
          <HelloWorld />
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<style>
body { font-family: Avenir, Helvetica, Arial, sans-serif; }
</style>
