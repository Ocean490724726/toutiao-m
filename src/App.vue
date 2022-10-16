<template>
  <div id="app">
    <h1>北昌教育</h1>
    <router-view />
    <!-- 测试iconfont -->
    <div>
      <i class="beichang beichang-chart"></i>
    </div>
    <!-- 测试vant -->
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
  </div>
</template>

<style lang="less"></style>
