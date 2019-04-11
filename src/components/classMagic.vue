<template>
  <div class="class-magic">
    <div class="header">
      <img class="back-icon" src="../assets/back.png" alt="返回">
      <div class="back-title">课堂魔镜</div>
    </div>

    <div class="content">
      <div class="c-tit">秋季班初中三年级数学尖子班（双师课堂）</div>
      <div class="c-lab">专注勋章日历</div>
      <img class="c-gold" src="../assets/gold.png" alt="奖牌">
      <div class="c-foot">张晓明本次课很专心，奖励专注金牌一枚！再接再厉哦！</div>
    </div>

    <div class="footer">
      <div class="min f-one">
        <span>1</span>
        <img class="flower" src="../assets/flower.png" alt="小奖章">
      </div>
      <div class="min">
        <span>2</span>
        <img class="flower" src="../assets/flower.png" alt="小奖章">
      </div>
      <div class="min">
        <span>3</span>
        <img class="flower" src="../assets/flower.png" alt="小奖章">
      </div>
      <div class="min">
        <span>4</span>
        <div>5月27日</div>
      </div>
      <div class="min">
        <span>5</span>
        <div>5月27日</div>
      </div>
      <div class="min f-six">
        <span>6</span>
        <div>5月27日</div>
      </div>
      <div class="min">
        <span>7</span>
        <div>5月27日</div>
      </div>
      <div class="min">
        <span>8</span>
        <div>5月27日</div>
      </div>
      <div class="min">
        <span>9</span>
        <div>5月27日</div>
      </div>
      <div class="min">
        <span>10</span>
        <div>5月27日</div>
      </div>
      <p class="f-footer">累计7枚金牌可找辅导老师加X积分哦～</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.class-magic {
  height: 12rem;
  width: 7.5rem;
}
.header {
  margin-bottom: 0.2rem;
  position: relative;
  width: 7.5rem;
}
.back-icon {
  display: inline-block;
  position: relative;
  width: 0.2rem;
  left: 0.3rem;
}
.back-title {
  display: inline-block;
  width: 7.5rem;
  height: 0.4rem;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-left: -4rem;
  font-size: 0.36rem;
  line-height: 0.4rem;
  text-align: center;
}
.content {
  position: relative;
}
.c-tit {
  font-size: 0.2rem;
  width: 7.5rem;
  height: 0.5rem;
  line-height: 0.5rem;
  text-align: center;
  color: rgb(153, 161, 181);
  padding-bottom: 2rem;
}
.c-lab {
  position: absolute;
  left: 50%;
  top: 50%;
  font-size: 0.28rem;
  width: 2.18rem;
  height: 0.48rem;
  text-align: center;
  line-height: 0.48rem;
  background-color: rgb(60, 66, 86);
  border-radius: 24px;
  margin: 0 auto;
  margin-left: -1.2rem;
  color: rgb(236, 236, 236);
}
.c-gold {
  position: absolute;
  width: 2.4rem;
  height: 2.74rem;
  top: 50%;
  left: 50%;
  margin-left: -1.3rem;
  margin-top: 0.8rem;
}
.c-foot {
  position: absolute;
  font-size: 0.26rem;
  width: 7.5rem;
  text-align: center;
  height: 0.5rem;
  line-height: 0.5rem;
  top: 50%;
  margin-top: 4rem;
}
.footer {
  margin-top: 4rem;
  width: 7.5rem;
}
.footer .min {
  position: relative;
  width: 1.34rem;
  height: 1.34rem;
  background-color: rgb(235, 236, 238);
  float: left;
  margin: 0.025rem;
  text-align: center;
}
.footer .f-one {
  margin-left: 0.3rem;
}
.footer .f-six {
  margin-left: 0.3rem;
}
.min .flower {
  width: .64rem;
  height: .73rem;
}
.f-footer {
  position: absolute;
  margin-top: 3.2rem;
  font-size: 0.24rem;
  width: 7.5rem;
  text-align: center;
  color: #99a1b5;
}
.footer span {
  position: absolute;
  text-align: center;
  font-size: .2rem;
  width: .34rem;
  height: .26rem;
  top: 0;
  left: 0;
  line-height: .26rem;
  background-color: rgb(221, 223, 230);
}
.min div {
  font-size: .2rem;
  text-align: center;
  color: #b6b9bd;
  width: 1.34rem;
  height: 1.34rem;
  line-height: 1.34rem;
}
</style>
