<template>
  <div class="home">
    <home-nav-bar />
    <div class="banner">
      <img src="@/assets/img/home/banner.webp" alt="" />
    </div>
    <div class="location">
      <div class="city">广州</div>
      <div class="position">
        <span class="text">我的位置</span>
        <img src="@/assets/img/home/icon_location.png" alt="" />
      </div>
    </div>
  </div>
</template>
<script setup>
import homeNavBar from "./cpns/home-nav-bar.vue";
</script>
<style lang="less" scoped>
.banner {
  img {
    width: 100%;
  }
}
.location {
  display: flex;
  height: 44px;
  align-items: center;
  padding: 0 20px;
  .city {
    flex: 1;
  }
  .position {
    width: 74px;
  }
  .text {
    position: relative;
    top: 2px;
    font-size: 12px;
  }
  img {
    margin-left: 5px;
    width: 18px;
    height: 18px;
  }
}
</style>
