<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/home-1.svg" alt="">
      <div slot="item-name">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img slot="item-icon" src="~assets/img/tabbar/item.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/item-1.svg" alt="">
      <div slot="item-name">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="~assets/img/tabbar/shopping-cart.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/shopping-cart-1.svg" alt="">
      <div slot="item-name">购物🚗</div>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/profile-1.svg" alt="">
      <div slot="item-name">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "components/common/tabbar/Tabbar";
  import TabBarItem from "components/common/tabbar/TabBarItem";

    export default {
        name: "MainTabBar",
      components: {
        TabBar,
        TabBarItem
      }
    }
</script>

<style scoped>

</style>
