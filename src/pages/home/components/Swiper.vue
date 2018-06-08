<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide>
        <img class="swiper-img" src="http://img1.qunarzz.com/piao/fusion/1805/13/6332699c44387902.jpg_750x200_b7afa4f8.jpg"/>
      </swiper-slide>
      <swiper-slide>
        <img class="swiper-img" src="http://img1.qunarzz.com/piao/fusion/1805/77/f63bd04dd5319602.jpg_750x200_6ba8e0ca.jpg"/>
      </swiper-slide>
      <div class="swiper-pagination"  slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {}
    }
  }
}
</script>

<style lang="stylus" scoped>
  .wrapper
    overflow: hidden
    width: 100%
    height: 0
    padding-bottom: 31.25%
    .swiper-img
      width: 100%
</style>
