<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: 'picgo'
  }
</script>

<style lang="stylus">
  body,
  html
    padding 0
    margin 0
    height 100%
    font-family "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif
  #app
    overflow-x hidden
    user-select none
  .el-button-group
    width 100%
    .el-button
      width 50%
  *::-webkit-scrollbar
    width 8px
    height 8px
  *::-webkit-scrollbar-thumb
    border-radius 4px
    background #6f6f6f
  *::-webkit-scrollbar-track
    background-color transparent
</style>
