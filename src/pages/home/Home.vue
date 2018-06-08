<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <div>test</div>
  </div>
</template>

<script>
import HomeHeader from './components/Head'
import HomeSwiper from './components/Swiper'
export default {
  name: 'Home',
  components: {
    HomeHeader, HomeSwiper
  }
}
</script>

<style>

</style>
