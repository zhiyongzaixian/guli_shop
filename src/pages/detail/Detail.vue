<template>
  <div id="detail">
    <Nav/>
    <div class="xiangqing">
      <div class="neirong w">
        <div class="xiaomi6 fl">小米88</div>
        <nav class="fr">
          <li><a href="">概述</a></li>
          <li>|</li>
          <li><a href="">变焦双摄</a></li>
          <li>|</li>
          <li><a href="">设计</a></li>
          <li>|</li>
          <li><a href="">参数</a></li>
          <li>|</li>
          <li><a href="">F码通道</a></li>
          <li>|</li>
          <li><a href="">用户评价</a></li>
          <div class="clear"></div>
        </nav>
        <div class="clear"></div>
      </div>
    </div>

    <div class="jieshao mt20 w clearfix">
      <div class="left fl" style="position: relative;">
        <div class="hiddenbox">
        </div>
        <img src="/static/image/detail/xiaomi6_small.jpg">
        <div class="smallbox"></div>
        <div class="bigbox">
          <img src="/static/image/detail/xiaomi6_big.jpg">
        </div>
        <div class="swiper-container swiper-container-horizontal">
          <div class="swiper-wrapper">
            <div class="swiper-slide active">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
            <div class="swiper-slide">
              <img src="/static/image/detail/liebiao_xiaomi6.jpg" alt="">
            </div>
          </div>
          <!-- Add Arrows -->
          <div class="swiper-button-next" style="background-color:#fff;height:100%"></div>
          <div class="swiper-button-prev swiper-button-disabled" style="background-color:#fff;height:100%"></div>
        </div>
      </div>
      <div class="right fr">
        <div class="h3 ml20 mt20">小米6</div>
        <div class="jianjie mr40 ml20 mt10">变焦双摄，4 轴防抖 / 骁龙835 旗舰处理器，6GB 大内存，最大可选128GB 闪存 / 5.15" 护眼屏 / 四曲面玻璃/陶瓷机身</div>
        <div class="jiage ml20 mt10">2499.00元</div>
        <div class="ft20 ml20 mt20">选择版本</div>
        <div class="xzbb ml20 mt10">
          <div class="banben fl">
            <a>
              <span>全网通版 6GB+64GB </span>
              <span>2499元</span>
            </a>
          </div>
          <div class="banben fr">
            <a>
              <span>全网通版 6GB+128GB</span>
              <span>2899元</span>
            </a>
          </div>
          <div class="banben fl">
            <a>
              <span>联通版 6GB+64GB </span>
              <span>2299元</span>
            </a>
          </div>
          <div class="banben fl">
            <a>
              <span>移动版 6GB+64GB </span>
              <span>2199元</span>
            </a>
          </div>
          <div class="clear"></div>
        </div>
        <div class="ft20 ml20 mt20">选择颜色</div>
        <div class="xzbb ml20 mt10">
          <div class="banben">
            <a>
              <span class="yuandian"></span>
              <span class="yanse">亮黑色</span>
            </a>
          </div>

        </div>
        <div class="xqxq mt20 ml20">
          <div class="top1 mt10">
            <div class="left1 fl">小米6 全网通版 6GB内存 64GB 亮黑色</div>
            <div class="right1 fr">2499.00元</div>
            <div class="clear"></div>
          </div>
          <div class="bot mt20 ft20 ftbc">总计：2499元</div>
        </div>
        <div class="xiadan ml20 mt20">
          <input class="jrgwc" type="button" name="jrgwc" value="立即选购"/>
          <input class="jrgwc" type="button" name="jrgwc" value="加入购物车"/>

        </div>
      </div>
      <div class="clear"></div>
    </div>
  </div>
</template>
<script>
  import Swiper from 'swiper'

  export default {
    mounted() {
      new Swiper('.swiper-container', {
        slidesPerView: 5,
        centeredSlides: false,
        spaceBetween: 30,
        pagination: {
          el: '.swiper-pagination',
          clickable: true,
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        },
      })
    },
  }
</script>
<style lang="stylus" scoped>
  #detail
    .xiangqing
      width 100%
      height 58px
      background rgb(240, 240, 240)
      .neirong
        height 58px
        width 1226px
        .xiaomi6
          width 300px
          height 58px
          line-height 58px
          font-size 22px
          font-weight bold
        nav
          display inline-block
          width 410px
          height 58px
          line-height 58px
          li
            font-size 14px
            float left
            display block
            margin 0px 5px
            a
              color #333
              font-size 14px
              &:hover
                color #ff6700

    .jieshao
      .left
        width 560px
        > img
          width 100%
          height 100%
        .smallbox
          display none
          background-color rgba(0, 255, 0, 0.3)
          width 280px
          height 280px
          position absolute
          top 0
          left 0
        .bigbox
          display none
          width 560px
          height 560px
          position absolute
          top -1px
          right -562px
          border 1px solid #ccc
          overflow hidden
          > img
            position absolute;
            left 0
            top 0
            height 1120px
            width 1120px
        .hiddenbox
          position absolute
          height: 560px
          left 0
          top 0
          right 0
          z-index 10
          border 1px solid #ccc
          &:hover
            ~ .smallbox
              display block
            ~ .bigbox
              display block
        .swiper-container
          width: 100%;
          height: 75px;
          margin: 20px auto;
          padding 0 34px;
          box-sizing border-box
          .swiper-wrapper
            .swiper-slide
              box-sizing border-box
              &.active
                border 3px solid red
              img
                width: 100%;
                height: 100%;
                cursor pointer
          .swiper-button-next,
          .swiper-button-prev
            height: 58px;
            width: 35px
            top: 22px;

          .swiper-button-prev
            left: 0;
            background-position: left;

          .swiper-button-next
            right: 0;
            background-position: right;

      .right
        width 620px
        background rgb(248, 248, 248)
        padding-bottom 50px
        .jianjie
          font-size 14px
          color rgb(176, 176, 176)
          line-height 20px
        .jiage
          font-size 18px
          color #ff6700
          font-weight bold
        .xzbb
          min-height 58px
          line-height 58px
          .banben
            height 58px
            float left
            line-height 58px
            width 290px
            cursor pointer
            margin-right 5px
            margin-bottom 3px
            border 1px solid #bbb
            a
              display block
              font-size 18px
              color #000
              padding 0 10px
              span
                display inline-block
                margin-right 10px
              .yuandian
                display inline-block
                height 15px
                width 15px
                border-radius 50%
                background #000
                margin-left 80px
          .active
            border 1px solid #ff6700
            a
              color #ff6700
        .xqxq
          height 80px
          width 555px
          background rgb(255, 255, 255)
          padding 20px
        .xiadan
          height 50px
          line-height 50px
          .jrgwc
            height 50px
            width 200px
            border none
            background #ff6700
            color #fff
            font-size 18px
            font-weight bold
            cursor pointer
            margin-right 50px
            &:hover
              border 1px solid #fff


</style>
