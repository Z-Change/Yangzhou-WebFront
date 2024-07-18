
 <template>
  <div class="about">
    <s-header :name="'关于我们'"></s-header>
    <van-nav-bar title="中专422团队" />
    <van-row justify="center">
      <van-col class="col" span="4">
        <van-image class="vimg" round fit="cover"
          src="https://avatars.githubusercontent.com/u/94502919?v=4" alt="" />
        <div style="font-size:20px;">张承志</div>
      </van-col>
      <van-col class="col" span="4">
        <van-image class="vimg" round fit="cover"
          src="https://avatars.githubusercontent.com/u/105236477?v=4" alt="" />
        <div style="font-size:20px;">施棋文</div>
      </van-col>
      <van-col class="col" span="4">
        <van-image class="vimg" round fit="cover"
          src="https://avatars.githubusercontent.com/u/95118308?v=4" alt="" />
        <div style="font-size:20px;">阳杰</div>
      </van-col>
      <van-col class="col" span="4">
        <van-image class="vimg" round fit="cover"
          src="https://avatars.githubusercontent.com/u/100596595?v=4" alt="" />
        <div style="font-size:20px;">田子瑞</div>
      </van-col>
      <van-col class="col" span="4">
        <van-image class="vimg" round fit="cover"
          src="https://avatars.githubusercontent.com/u/106143646?v=4" alt="" />
        <div style="font-size:20px;">何嘉浩</div>
      </van-col>
    </van-row>
    <div class="about-body">
      <!-- <img class="intro-img" src="https://s.yezgea02.com/1604046067055/WechatIMG30231.jpeg" alt=""> -->
      <van-divider
        :style="{ color: '#FB7299', borderColor: '#FB7299', fontSize: '20px', fontWeight: 500 }">简介
      </van-divider>
      <div>pilipili-mall 项目是一套电商系统，包括 pilipili-mall 商城系统及 pilipili-mall-admin 商城后台管理系统，基于 Spring
        Boot 3.X
        及相关技术栈开发。 前台商城系统包含首页门户、商品分类、新品上线、首页轮播、商品推荐、商品搜索、商品展示、购物车、订单结算、订单流程、个人订单管理、会员中心等模块。
        后台管理系统包含数据面板、轮播图管理、商品管理、订单管理、会员管理、分类管理、设置等模块。</div>
      <van-divider
        :style="{ color: '#FB7299', borderColor: '#FB7299', fontSize: '20px', fontWeight: 500 }">
        开源地址</van-divider>
      <div>
        <div>后端 API 地址：<a target="_blank"
            href="https://github.com/Z-Change/Yangzhou-WebBack">https://github.com/Z-Change/Yangzhou-WebBack</a>
        </div>
        <br />
        <div>前端 Vue3.x + Vant4.x 开源地址：<a target="_blank"
            href="https://github.com/Z-Change/Yangzhou-WebFront">https://github.com/Z-Change/Yangzhou-WebFront</a>
        </div>
        <br />
        <div>线上预览地址：<a target="_blank" href="http://zcz1.site">http://vue-app.pilipili</a></div>
      </div>
    </div>
  </div>
</template>

<script setup>
import sHeader from '@/components/SimpleHeader.vue';
</script>

<style lang="less" scoped>
.col {
  text-align: center;
  margin-top: 10px;
  .vimg {
    width: 100px;
    height: 100px;
  }
}
.about {
  box-sizing: border-box;
  padding: 20px;
  .intro-img {
    width: 100%;
  }
  .about-body {
    font-size: 16px;
    a {
      color: #007fff;
    }
  }
}
</style>
