<template>
<<<<<<< HEAD
  <div>
      TopBar
=======
  <div class="top-bar">
    <div class="wrap top-bar-wrap">
      <div class="left">欢迎来到叩丁狼积分商城</div>
      <ul class="right">
        <li>
          <img src="../assets/img/userImg.f8bbec5e.png" alt="" class="avatar" />
        </li>
        <li>用户名：游客</li>
        <li>我的积分：--</li>
        <li>获取积分</li>
        <li>扣丁狼官网</li>
        <li class="login-btn">登录</li>
      </ul>
    </div>
>>>>>>> bea6181 (完成了TopBar的基本样式)
  </div>
</template>

<script>
export default {
<<<<<<< HEAD
name:'TopBar'
=======
  name: 'TopBar',
>>>>>>> bea6181 (完成了TopBar的基本样式)
}
</script>

<style lang="less" scoped>
<<<<<<< HEAD

</style>
=======
.top-bar {
  height: 40px;
  background-color: #242b39;
  .top-bar-wrap {
    display: flex;
    justify-content: space-between;
    height: 40px;
    line-height: 40px;
    color: #dfdfe0;
    .right {
      display: flex;
      height: 14px;
      font-family: SourceHanSansSC-Light;
      font-size: 14px;
      li {
        margin-left: 20px;
        cursor: pointer;
        .avatar {
          width: 26px;
          border-radius: 50%;
          vertical-align: middle;
        }
        &.login-btn {
          width: 124px;
          height: 40px;
          text-align: center;
          background-color: #0a328e;
        }
      }
    }
  }
}
</style>
>>>>>>> bea6181 (完成了TopBar的基本样式)
