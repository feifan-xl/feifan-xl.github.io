<script setup>
import ParentLayout from '@vuepress/theme-default/layouts/Layout.vue'
</script>

<template>
  <ParentLayout>
    <template #navbar-after>
      <a href="./">home</a>
      <span style="display: inline-block; width: 20px;"></span>
      <a href="./guide">guide</a>
    </template>
  </ParentLayout>
</template>

<style lang="css">
.my-footer {
  text-align: center;
}
</style>