<template>
  <div class="layout">
    <main>
      <router-view />
    </main>
    <van-tabbar route>
      <van-tabbar-item to="/home" icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item to="/cent" icon="search">个人</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped lang="less">
.layout {
  width: 100vw;
  height: 100vh;
  main {
    height: calc(100vh - var(--van-tabbar-height));
  }
}
</style>
