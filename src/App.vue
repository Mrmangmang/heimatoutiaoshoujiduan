<template>
  <div id="app">
     <h1>黑马头条</h1>
<!--    路由出口-->
    <router-view/>
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>

    <van-cell-group>
        <van-cell title="单元格" value="内容" />
        <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
      <!-- 手机图标 -->
      <i class="toutiao toutiao-shouji"></i>

      <!-- 收藏图标 -->
      <i class="toutiao toutiao-shoucang"></i>
      <!-- 基本展示 -->
      <van-icon name="chat-o" />

      <!-- 设置dot属性后，会在图标右上角展示一个小红点 -->
      <van-icon name="chat-o" dot />

      <!-- 设置badge属性后，会在图标右上角展示相应的徽标 -->
      <van-icon name="chat-o" badge="9" />
  </div>
</template>



<style lang="less">

</style>
