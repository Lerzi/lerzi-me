<script setup lang="ts">
import { toggleDark } from '~/composables'
</script>

<template>
  <div flex="~" justify-between h-16 px-20 border-b-2>
    <div flex="~" items-center>
      LERZI
    </div>
    <Menus />
    <nav flex="~" items-center text-xl>
      <button class="icon-btn mx-2 !outline-none" title="切换颜色" @click="toggleDark()">
        <div i="carbon-sun dark:carbon-moon" />
      </button>

      <a class="icon-btn mx-2" rel="noreferrer" href="https://github.com/Lerzi/" target="_blank" title="GitHub">
        <div i-carbon-logo-github />
      </a>
    </nav>
  </div>
</template>

