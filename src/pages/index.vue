<script setup lang="ts">
</script>

<template>
  <div flex="~ col" gap-5>
    <h1 text-4xl mb-5>
      LERZI
    </h1>
    <div>
      Yo! 我是黄顺，一个前端工程师
    </div>
    <div>
      主要使用技术栈是<span px2 text-xl text-pink-600 font-bold>Vue</span>
    </div>
    <div>
      如果你想看我的个人项目，可以
      <router-link to="/projects" px2 hover:text-pink-600 font-bold delay-100>
        点击这里
      </router-link>
    </div>
    <!-- <div>
      你可以通过添加我的 微信 与我取得联系，但请说明来意
    </div> -->
  </div>
</template>
<!--
<route lang="yaml">
meta:
  layout: home
</route> -->
