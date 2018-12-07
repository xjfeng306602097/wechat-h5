<template lang="html">

  <div class="service">
    <ul>
      <li style="width:20%"><img src="../../assets/index/images/youhui.jpg" class="icon-99"/></li>
      <li style="width:20%"><img src="../../assets/index/images/juhuasuan.jpg" class="icon-99"/></li>
      <li style="width:20%"><img src="../../assets/index/images/baoyou.jpg" class="icon-99"/></li>
    </ul>
    <ul>
      <li><i class="icon-99"></i><span>优惠券</span></li>
      <li><i class="icon-99"></i><span>聚划算</span></li>
      <li><i class="icon-99"></i><span>9.9包邮</span></li>
    </ul>
    <ul>
      <li style="width:20%"><img src="../../assets/index/images/category.jpg" class="icon-99"/></li>
      <li style="width:20%"><img src="../../assets/index/images/pingtuan.jpg" class="icon-99"/></li>
      <li style="width:20%"><img src="../../assets/index/images/baoyou.jpg" class="icon-99"/></li>
    </ul>
    <ul>
      <li><i class="icon-99"></i><span>今日推荐</span></li>
      <li><i class="icon-99"></i><span>拼团</span></li>
      <li><i class="icon-99"></i><span>免单福利</span></li>
    </ul>
  </div>
</template>

<style lang="less" scoped>
  @import '../../assets/fz.less';
  @import '../../assets/index/style.css';
  .service {
    .bd();
    ul {
      display: -webkit-flex;
      display: -ms-flex;
      display: flex;
      justify-content: space-around;

      li {
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        padding: 3.3vw 0;
        span {
          .fz(font-size,28);
          padding-left: 1vw;
        }
        i {
          .fz(font-size,36);
        }
      }
    }
  }

</style>
