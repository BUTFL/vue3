
<template>
  <div>
    <n-carousel autoplay class="nva" interval=6000 show-arrow>
      <img
          class="carousel-img"
          src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fpic.jj20.com%2Fup%2Fallimg%2F1113%2F0F220091915%2F200F2091915-10-1200.jpg&refer=http%3A%2F%2Fpic.jj20.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1634661671&t=3dc6d47f2f0fc105166a3b4506087d0d"
      />
      <img
          class="carousel-img"
          src="https://img.sanhao.com/community_news/28318/2018090614513325.jpg"
      />
      <img
          class="carousel-img"
          src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.zcool.cn%2Fcommunity%2F01a7245bcc273fa801213dea25922c.jpg%401280w_1l_2o_100sh.jpg&refer=http%3A%2F%2Fimg.zcool.cn&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1634661831&t=63389e3c84faa55d638f2a75376a98df"
      />
    </n-carousel>
    <div style="text-align: center;margin-top: 20px">
      <div style="font-size: 22px">我们的服务</div>
      <div style="font-size: 20px ;color: #999">Our services</div>
      <div style="border-bottom: 5px solid red;width: 50px;margin: 0px auto"></div>
    </div>
    <div class="img">
      <div
           class="wow slideInLeft" data-wow-duration="2s" data-wow-delay="5s"
      >
        <img alt="" src="https://zos.alipayobjects.com/rmsportal/WBnVOjtIlGWbzyQivuyq.png" style="width: 120px">
        <div>今日排名第<span>1</span>名</div>
      </div>
      <div
          class="wow slideInLeft" data-wow-duration="2s" data-wow-delay="5s"
      >
        <img alt="" src="https://zos.alipayobjects.com/rmsportal/YPMsLQuCEXtuEkmXTTdk.png" style="width: 120px">
        <div>今日课程排序</div>
      </div>
      <div
          class="wow slideInLeft" data-wow-duration="2s" data-wow-delay="5s"
      >
        <img alt="" src="https://zos.alipayobjects.com/rmsportal/EkXWVvAaFJKCzhMmQYiX.png" style="width: 120px">
        <div>今日数据统计</div>
      </div>
    </div>

    <div style="text-align: center;margin-top: 40px">
      <div style="font-size: 22px">我们的流程</div>
      <div style="font-size: 20px ;color: #999">Our process</div>
      <div style="border-bottom: 5px solid red;width: 50px;margin: 0px auto"></div>
    </div>
    <div style=" margin-top: 40px">
      <n-space style="width: 450px;margin: 0px auto;" vertical>
        <n-steps :current="current" :status="currentStatus" vertical>
          <n-step
              description="首先，企业需要有确定的目标，这个目标要可执行、可拆解甚至可衡量，输入初始状态的企业，输出符合目标描述的企业，每个项目都要有明确的目标。"
              title="项目启动阶段"
          />
          <n-step
              description="项目规划阶段包括确定工作任务，任务分解，安排优先级，预算成本和风险管理。项目计划和控制是项目管理的主线，贯穿项目管理的全过程。为了使一个项目成功任务，必须有一个良好的计划与控制。任务分解就是项目管理中的WBS原则：从项目目标开始分解，逐层下降，每下降一层，代表对项目工作的更详细的定义，将任务分解到不能再分为止。"
              title="规划阶段"
          />
          <n-step description="现在为止项目已经万事俱备了，开始着手项目的实施。开始具体分配任务，确认每个任务的开始/截止时间、优先级等。在执行管理中最重要的沟通管理，成员之间的有效沟通，是为了确保项目的信息的合理收集和传输所需要实施的一系列措施，它包括沟通规划，信息传输和进度报告等。"
                  title="执行阶段"
          />
          <n-step
              description="监控项目工作是跟踪、审查和报告项目进展，以实现项目管理计划中确定的绩效目标的过程。最常用的就是用甘特图监控项目进度。也有些企业需要统计工时等来做员工绩效考核的，是情况而定。"
              title="监控阶段"
          />
          <n-step
              description="结束项目是完结项目管理所有活动以正式结束项目或阶段的过程。在项目结束后，项目经理需要审查以前各阶段的收尾信息，确保所有项目工作已完成。现在有多公司用项目管理软件做项目管理，既能实现公司化管理，又能提高工作效率。"
              title="收尾阶段"
          />
        </n-steps>
      </n-space>
    </div>

    <div style="margin-top: 50px;height: 500px">
      <div>
        <img alt="" src="https://i.loli.net/2021/09/19/e3OaJrvCAwTBDiW.png" width="100%">
      </div>
    </div>

    <div style="text-align: center;font-size: 22px">行业咨询</div>
    <div style="text-align: center;font-size: 20px;color:#999;">Industry consultancy</div>
    <div style="border-bottom: 5px solid red;width: 50px;margin: 0px auto"></div>
    <div class="content-center" style="margin-top: 40px;display: flex;justify-content: space-around;width: 80%">
      <div class="content">
        <div class="title">信息咨询</div>
        <div class="title-one">Information consultation</div>

        <img class="img_url" alt="" src="http://image.photocnc.com/photocnc/2020-10/29/202010291252037469.Jpeg.w1680.jpg"
             style="width: 300px">
        <div>
          <ul>
            <li>成就自己只需要一套精品</li>
            <li>成就自己只需要一套精品</li>
            <li>成就自己只需要一套精品</li>
          </ul>
        </div>
      </div>
      <div class="content">
        <div class="title">地址查询</div>
        <div class="title-one">Address the query</div>
        <img class="img_url" alt="" src="https://img.sanhao.com/community_news/28318/2018090614513325.jpg" style="width: 300px">
        <div>
          <ul>
            <li>成就自己只需要一套精品</li>
            <li>成就自己只需要一套精品</li>
            <li>成就自己只需要一套精品</li>
          </ul>
        </div>
      </div>
      <div class="content">
        <div class="title">公司动态</div>
        <div class="title-one">The company dynamic</div>
        <img class="img_url" alt="" src="https://cdn.wallpapersafari.com/47/55/Sg5pZF.jpg" style="width: 300px">
        <div>
          <ul>
            <li>成就自己只需要一套精品</li>
            <li>成就自己只需要一套精品</li>
            <li>成就自己只需要一套精品</li>
          </ul>
        </div>
      </div>
    </div>
    <div style="text-align: center;font-size: 22px;margin-top: 40px">今日用户统计</div>
    <div style="text-align: center;font-size: 20px;color:#999;">Today's User Statistics</div>
    <div style="border-bottom: 5px solid red;width: 50px;margin: 0px auto"></div>
    <div style="display: flex;justify-content: space-around;margin-top: 40px">
      <div>
        <n-progress :percentage="70" style="width: 300px" type="circle"/>
        <div style="font-size: 25px ;margin-top: 20px;text-align: center">今日完成注册用户</div>
      </div>
      <div>
        <n-progress :percentage="100" color="red" style="width: 350px" type="circle"/>
        <div style="font-size: 25px;margin-top: 20px;text-align: center">今日销售</div>
      </div>
      <div>
        <n-progress :percentage="85" color="green" style="width: 300px" type="circle"/>
        <div style="font-size: 25px;margin-top: 20px;text-align: center">今日完成下载用户</div>
      </div>
    </div>
  </div>
</template>
<script>
import {defineComponent} from 'vue'
import {NCarousel, NSpace, NResult, NProgress, NSteps, NStep} from 'naive-ui'
import {MdArrowRoundBack, MdArrowRoundForward, MdSave} from '@vicons/ionicons4'
export default defineComponent({
  components: {
    MdArrowRoundBack,
    NSteps,
    NStep,
    MdSave,
    NProgress,
    MdArrowRoundForward,
    NCarousel,
    NResult,
    NSpace,
  }
})

</script>
<style scoped>
.carousel-img {
  width: 100%;
  height: 653px;
}

.nva {
  width: 100%;
  height: 650px;
  margin: 0px auto;
}

.img {
  display: flex;
  justify-content: space-around;
  margin-top: 40px
}

.img_one > div {
  font-size: 20px;
  text-align: center;
  color: #999999;
}

.content {
  text-align: center;
  font-size: 16px;
}

.title {
  font-size: 18px;
}
.title-one {
  color: #999999;
}

.content-center {
  margin: 0px auto;
}
</style>
