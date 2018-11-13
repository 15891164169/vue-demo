<template>
  <div id="app">
    <mt-header fixed title="固定在顶部"></mt-header>
    <p>ad</p>
    <router-view></router-view>

    <nav class="mui-bar mui-bar-tab">
      <router-link tag="section" class="mui-tab-item" to="/tabbar">
        <span class="mui-icon mui-icon-home"></span>
        <span class="mui-tab-label">首页</span>
      </router-link>
      <router-link tag="section" class="mui-tab-item" to="/member">
        <span class="mui-icon mui-icon-contact"></span>
        <span class="mui-tab-label">会员</span>
      </router-link>
      <router-link tag="section" class="mui-tab-item" to="/cart">
        <span class="mui-icon mui-icon-extra mui-icon-extra-cart"><span class="mui-badge">0</span></span>
        <span class="mui-tab-label">购物车</span>
      </router-link>
      <router-link tag="section" class="mui-tab-item" to="/search">
        <span class="mui-icon mui-icon-search"></span>
        <span class="mui-tab-label">搜索</span>
      </router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {

}
.mui-active {
  color: blue;
}
p {
  margin-top: 40px;
}
</style>
