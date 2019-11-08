<template>
  <div id="tab-bar">
      <div id="tab-bar-item">首页</div>
      <div id="tab-bar-item">分类</div>
      <div id="tab-bar-item">购物车</div>
      <div id="tab-bar-item">我的</div>
  </div>
</template>
<script>
export default {
  name:"TabBar",
}
</script>
<style>
#tab-bar{
  display: flex;
  background-color: #eee;
  position: fixed;
  left: 0px;
  right: 0px;
  bottom: 0px;
  box-shadow: 0 -1px 1px rgba(100,100,100, .2)
}
#tab-bar-item{
  flex: 1;
  text-align: center;
  height: 49px;
}
</style>