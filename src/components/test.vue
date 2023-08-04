<script lang="ts" setup>
import type { TestEmits } from './test'

const emits = defineEmits<TestEmits>()
</script>

<template>
  <div btn @click="emits('go')">
    点击我会有警告在控制台
  </div>
</template>
