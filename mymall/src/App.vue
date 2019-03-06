<template>
  <div class="g-container" id="app">
		<div class="g-view-container">
      <!-- 显示不同页面组件 -->
      <router-view></router-view>
    </div>
		<div class="g-footer-container">
      <!-- 底部导航实现列表超链接 -->
      <tabbar></tabbar>
		</div>
	</div>
</template>

<script>
//导入tabbar组件
import tabbar from "@/components/tabbar";
export default {
  name: 'App',
  components: {
    tabbar
  }
};
</script>

<style>
</style>
