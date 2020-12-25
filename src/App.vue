<template>
  <div id="app" class="wrap_w">
    <el-menu
      :default-active="activeIndex"
      class="el-menu-demo"
      mode="horizontal"
      @select="handleSelect"
    >
      <el-menu-item index="1">处理中心</el-menu-item>
      <el-submenu index="2">
        <template slot="title">我的工作台</template>
        <el-menu-item index="2-1">选项1</el-menu-item>
        <el-menu-item index="2-2">选项2</el-menu-item>
        <el-menu-item index="2-3">选项3</el-menu-item>
        <el-submenu index="2-4">
          <template slot="title">选项4</template>
          <el-menu-item index="2-4-1">选项1</el-menu-item>
          <el-menu-item index="2-4-2">选项2</el-menu-item>
          <el-menu-item index="2-4-3">选项3</el-menu-item>
        </el-submenu>
      </el-submenu>
      <el-menu-item index="3">消息中心</el-menu-item>
      <el-menu-item index="4">
        <a href="https://www.ele.me" target="_blank">订单管理</a>
      </el-menu-item>
    </el-menu>

    <!--轮播区域-->
    <Carousel></Carousel>
    <!--每天一次打卡 收获一份惊喜-->
    <div class="wrap_ww">
      <Clock></Clock>
    </div>
    <!--参与共享活动 实现财富增值-->
    <Join></Join>
    <!--热门共享-->
    <div class="wrap_ww">
      <Share></Share>
    </div>
    <!--<router-view/>-->
  </div>
</template>
<script>
import Carousel from "./components/Carousel";
import Clock from "./components/Clock";
import Join from "./components/Join";
import Share from "./components/Share";
export default {
  name: "App",
  components: {
    Carousel,
    Clock,
    Join,
    Share,
  },
  data() {
    return {
      activeIndex: "1",
      activeIndex2: "1",
    };
  },
  methods: {
    handleSelect(key, keyPath) {
      console.log(key, keyPath);
    },
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
