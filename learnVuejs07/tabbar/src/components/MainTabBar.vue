<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="blue">
        <img slot="item-icon" src="../assets/img/tabbar/index.png" alt="">
        <img slot="item-icon-active" src="../assets/img/tabbar/index_active.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>

      <tab-bar-item path="/category" activeColor="blue">
        <img slot="item-icon" src="../assets/img/tabbar/category.png" alt="">
        <img slot="item-icon-active" src="../assets/img/tabbar/category_active.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>

      <tab-bar-item path="/cart" activeColor="blue">
        <img slot="item-icon" src="../assets/img/tabbar/shopcart.png" alt="">
        <img slot="item-icon-active" src="../assets/img/tabbar/shopcart_active.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>

      <tab-bar-item path="/profile" activeColor="blue">
        <img slot="item-icon" src="../assets/img/tabbar/profile.png" alt="">
        <img slot="item-icon-active" src="../assets/img/tabbar/profile_active.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>

    </tab-bar>
  </div>
</template>

<script>

  // 1 导入组件
  import TabBar from "./tabbar/TabBar";
  import TabBarItem from "./tabbar/TabBarItem"


  export default {
    name: "MainTabBar",
    components: {  // 2 注册组件
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>
