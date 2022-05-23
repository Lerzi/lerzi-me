<script setup lang="ts">
const menus = ref([
  {
    title: '文章',
    path: '/article',
  },
  {
    title: '项目',
    path: '/project',
  },
  {
    title: '关于我',
    path: '/',
  },
])
</script>

<template>
  <div flex="~" items-center justify-center gap-2>
    <router-link
      v-for="item in menus" :key="item.path" :to="item.path"
      icon-btn flex="~" items-center justify-center h-full w-20 transition hover:bg-gray100
    >
      {{ item.title }}
    </router-link>
  </div>
</template>
