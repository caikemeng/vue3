<template>
  <div>
    <el-button type="primary" @click="increment">点击次数: {{ count }}</el-button>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
const increment = () => { count.value++ }
</script>

<style scoped>
div { margin-top: 16px; }
</style>
