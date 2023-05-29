<script setup>
import header from './components/header.vue'
import signin from './components/signin.vue'
import right_side from './components/right-side.vue'
import section from './components/section.vue'
</script>

<template>
  <header />
  <div style="float:left;width:50%;border-right:1px solid #000;height:600px;">
  <signin />
  </div>
  <div>
  <right_side />
  </div>
  <section />

</template>

<script>

</script>

<style scoped>

</style>