<script>

</script>

<template>
  <div class="footer">
    <div class="box-bottom bk" >
      <div class="box-bottom-top" style="">
        <div>网站首页 <span>联系我们</span></div>
        <div class="to">相关链接：<span>北京教育园区</span> <span>融职教育</span></div>
        <div class="to">合作资讯：<span>010-1241552681</span></div>
      </div>
    </div>
  </div>
</template>

<script>
import {defineComponent} from 'vue'
import {NSpace, NCard} from 'naive-ui'

export default defineComponent({
  components: {
    NSpace,
    NCard
  }
})
</script>
<style scoped>
* {
  margin: 0px;
  padding: 0px;
  list-style: none;
}
.footer{
  background: #001529;
}
.box-bottom {
  height: 121px;
  margin-top: 14px;
  color: #FFFFFF;
  font-size: 14px;
}
.box-bottom-top {
  width: 1442px;
  margin: 0 auto;
}
.box-bottom-top > .to {
  margin-top: 8px;
}
</style>
