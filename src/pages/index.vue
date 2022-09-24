<script setup lang="ts">
</script>

<template>
  <div flex="~ col" gap-5>
    <h1 text-4xl mb-5>
      LERZI
    </h1>
    <div>
      Yo! 我是黄顺，一个对开发保持着热情的前端工程师
    </div>
    <div>
      主要使用技术栈是<span px2 text-xl text-pink-600 font-bold>Vue</span>
    </div>
    <div>
      <router-link to="/projects" px2 hover:text-pink-600 font-bold delay-100>
        这里
      </router-link>
      可以看到我的一些项目
    </div>
  </div>
</template>
<!--
<route lang="yaml">
meta:
  layout: home
</route> -->
