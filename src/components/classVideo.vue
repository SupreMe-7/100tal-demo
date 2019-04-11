<template>
  <div class="class-video">
    <div class="v-header">
      <div class="state-video">
        <div class="text">课堂状态小视频</div>
      </div>
      <div class="shipin">
        <video src="../assets/video.mp4" controls></video>
      </div>
    </div>
    <div class="v-score">
      <div class="all">
        <img class="v-score-score" src="../assets/score.png" alt="评分">
        <p>报告评分</p>
        <div class="all-star">
          <ul>
          <li>
            <img class="star" src="../assets/goldstar.png" alt="goldstar">
            <img class="star" src="../assets/goldstar.png" alt="goldstar">
            <img class="star" src="../assets/goldstar.png" alt="goldstar">
            <img class="star" src="../assets/goldstar.png" alt="goldstar">
            <img class="star" src="../assets/star.png" alt="star">
          </li>
        </ul>
        </div>
        <textarea placeholder="请在此写下您对报告的宝贵建议"></textarea>
        <button class="sub" type="submit">提交</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.class-video {
  width: 7.5rem;
  height: 15rem;
}
.v-header {
  height: 6.5rem;
  width: 7.5rem;
  background-color: rgb(245, 245, 245);
}
.state-video {
  height: 1.9rem;
  width: 7.5rem;
  position: absolute;
}
.state-video .text {
  color: #ececec;
  position: relative;
  top: 50%;
  left: 50%;
  margin: -0.24rem 0 0 -1.24rem;
  border-radius: 0.24rem;
  background-color: rgb(60, 66, 86);
  width: 2.48rem;
  height: 0.48rem;
  line-height: 0.48rem;
  text-align: center;
  font-size: 0.28rem;
}
.shipin {
  position: relative;
}
video {
  position: absolute;
  top: 1.9rem;
  width: 6.9rem;
  height: 3.88rem;
  margin: 0 auto;
  left: 50%;
  margin: 0 0 0 -3.45rem;
}
.v-score {
  width: 7.5rem;
  height: 7.3rem;
  background-color: rgb(36, 43, 69);
  position: relative;
}
.v-score .all {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  margin-top: .2rem;
}

.v-score-score {
  position: relative;
  top: 50%;
  left: 50%;
  height: 1.2rem;
  width: 1.2rem;
  margin: -0.6rem 0 0 -0.6rem;
}
.v-score p {
  font-size: 0.3rem;
  color: #fff;
  position: relative;
  top: 50%;
  left: 50%;
  width: 1.2rem;
  height: .35rem;
  margin: -.175rem 0 0 -.6rem;
}
.v-score .all-star {
  position: relative;
  top: 50%;
  left: 50%;
  width: 3.47rem;
  height: .66rem;
  margin: -.33rem 0 0 -1.735rem;
}
.v-score .star {
  width: 0.42rem;
}
.v-score textarea {
  position: relative;
  left: 50%;
  width: 6.9rem;
  height: 2.28rem;
  border-radius: 0.06rem;
  margin: .8rem 0 0 -3.45rem;
}
.v-score .sub {
  position: relative;
  top: -.35rem;
  width: 6.9rem;
  height: .9rem;
  border-radius: .1rem;
  border: 1px solid #e26000;
  background-color: rgb(36, 43, 69);
  color: #e26000;
}
</style>
