<script>

</script>
<template>
  <div style="display: flex;align-items: center;justify-content: space-around;height: 80px;">
    <div style="font-size: 40px;color: cornflowerblue">LOGO</div>

    <div style="color: #999"><span>添加收藏</span> | <span>企业邮箱</span></div>
  </div>
  <div class="box">
    <ul>
      <li>首页</li>
      <li>关于我们
        <ul>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
        </ul>
      </li>
      <li>产品</li>
      <li>解决方案
        <ul>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
        </ul>
      </li>
      <li>服务</li>
      <li>网站域名
        <ul>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
        </ul>
      </li>
      <li>联系方式
        <ul>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
          <li>关于我们</li>
        </ul>
      </li>
      <li>更多</li>
    </ul>
  </div>
</template>
<style scoped>
* {
  margin: 0px;
  padding: 0px;
  list-style: none;
}

.box {
  width: 100%;
  z-index: 1;
  box-shadow: 1px 2px 8px rgb(0 0 0 / 15%);
  top: 2px;
}

.box > ul {
  color: #001529;
  width: 1080px;
  margin: 0px auto;
  display: flex;
  justify-content: space-around;
}

.box > ul > li {
  width: 60%;
  font-size: 14px;
  line-height: 60px;
  text-align: center;
  height: 60px;
}

.box > ul > :hover {

}

.box > ul > li {
  float: left;
  display: block;
  height: 40px;
  line-height: 40px;
  padding: 0 20px;
  position: relative;
}

.box > ul > li > ul > li {
  float: none;
}

.box > ul > li > ul {
  width: 100%;
  z-index: 100000;
  position: absolute;
  top: 40px;
  left: 0;
  display: none;
}

.box > ul li:hover ul {
  display: block;
  background: white;
}

.box > ul > li > ul > li:hover {
  background: #cccccc;
  color: #001529;
}
</style>
