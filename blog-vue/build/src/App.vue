<!--
 * @Descripttion: 
 * @version: 
 * @Author: sueRimn
 * @Date: 2022-04-29 16:37:51
 * @LastEditors: sueRimn
 * @LastEditTime: 2022-05-10 16:58:38
-->
<template>
  <div id="app">
    <router-view />
    <!-- <go-top></go-top> -->
  </div>
</template>

<script>
import GoTop from '@/components/gotop/GoTop'
export default {
  name: 'App',
  components: { GoTop }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
/* #app {
  border: 1px solid red;
  overflow: auto;
} */
body {
  background-color: #f5f5f5;
  font-weight: 400;
  font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
    "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
  line-height: 1.5;
}
a {
  cursor: pointer;
  text-decoration: none;
  transition: none 86ms ease-out;
}
a:hover {
  color: #5fb878;
}
.me-area {
  background-color: #fff;
}
html {
  height: 100%;
}
body {
  min-height: 100%;
}
body {
  position: relative;
}

.me-pull-right {
  float: right;
}
</style>
