<template>
  <div class="home">
    <div class="header"></div>
    <div class="sub-title"></div>
    <div class="sup-title"></div>
    <!-- <div class="content"></div> -->
    <div class="rule"></div>
    <div class="present-btn"></div>
  </div>
</template>

<script>
// import axios from '../assets/js/axios'

export default {
  name: 'Home',
  components: {},
}
</script>
<style lang="scss" scoped>
.home {
  // display: flex;
  // justify-content: center;
  // align-items: center;
  box-sizing: border-box;
  padding: 20px 30px;
  width: 100%;
  height: 100%;
  font-size: 50px;
  background: url('../assets/images/bg.png') no-repeat center center;
  background-size: 100% 100%;
  .header {
    height: 80px;
    background: url('../assets/images/header.png') no-repeat center center;
    background-size: contain;
  }
  .sub-title {
    height: 60px;
    background: url('../assets/images/sub-title.png') no-repeat center center;
    background-size: contain;
  }
  .sup-title {
    height: 60px;
    background: url('../assets/images/sup-title.png') no-repeat center center;
    background-size: contain;
  }
  .content {
     height: 260px;
    background: url('../assets/images/content.png') no-repeat center center;
    background-size: contain;
  }
  .present-btn {
    position: absolute;
    right: 10px;
    top: 75%;
    display: inline-block;
    width: 100px;
    height: 100px;
    background: url('../assets/images/present.png') no-repeat center center;
    background-size: contain;
  }
  .rule {
    position: absolute;
    right: 0;
    top: 30px;
    display: inline-block;
    width: 80px;
    height: 70px;
    background: url('../assets/images/rule.png') no-repeat center center;
    background-size: contain;
  }
}
</style>