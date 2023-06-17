<script setup lang="ts">
const str = '我爱你'
console.log(str)
</script>

<template>
  <div class="box">
    <h1>我是APP根组件</h1>
  </div>
</template>

<style scoped lang="scss">
.box {
  width: 600px;
  height: 400px;
  background: black;
  h1 {
    color: white;
  }
}
</style>
