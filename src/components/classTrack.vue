<template>
  <div class="class-track">
    <div class="t-head">
      <div class="h-genzong">课堂专注度跟踪</div>
    </div>
    <div class="t-content">
      <div class="h-swiper">
        <swiper />
      </div>
      <div class="t-echarts">
        <echarts />
      </div>
    </div>
    <div class="t-footer">
      <div>
        <img src="../assets/pingyu.png" alt="icon">
        <span>专注度评语</span>
      </div>
      <p>孩子听课很认真哦！打败了全班90%的同学！请继续努力！</p>
    </div>
  </div>
</template>

<script>
import swiper from './swiper.vue'
import echarts from './echarts.vue'
export default {
  components: {
    swiper,
    echarts
  }
};
</script>

<style>
.class-track {
  width: 7.5rem;
  height: 11.82rem;
  background-color: rgb(36, 43, 69);
}
.t-head {
  height: 2rem;
}
.t-head .h-genzong {
  position: relative;
  top: 0.7rem;
  left: 2.5rem;
  width: 2.48rem;
  height: 0.48rem;
  text-align: center;
  line-height: 0.48rem;
  background-color: rgb(236, 236, 236);
  font-size: 0.28rem;
  color: #3c4256;
  border-radius: 24px;
}
.t-content {
  width: 7.5rem;
  height: 7rem;
}
.t-content .t-echarts {
  height: 5.75rem;
  width: 7.5rem;
}
.t-footer {
  margin-left: .3rem;
}
.t-footer img {
  width: .3rem;
  height: .27rem;
}
.t-footer span {
  position: relative;
  font-size: .28rem;
  color: #99a1b5;
  left: -.15rem;
}
.t-footer p {
  font-size: .24rem;
  color: rgb(236, 236, 236);
}
</style>
