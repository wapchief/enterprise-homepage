<template>
  <div class="header">
    <!-- <img class="logo" src="../assets/logo.svg" />
    <img class="bg" src="../assets/footer.png" /> -->

    <div class="w">
      <a href="#/" class="logo"></a>
      <!---->
      <div class="user">
        <a>登录</a>&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;<a>注册</a>
      </div>
      <ul class="menu">
        <li><a>邀请有礼</a></li>
        <li>
          <a href="#/college" class="">所有院校</a>
        </li>
        <li>
          <a href="#/college/major" class="">课程中心</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Header to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
li {
  display: inline-block;
  vertical-align: middle;
  letter-spacing: 0;
  font-size: 14px;
  width: 120px;
  text-align: center;
  a {
    color: #fff;
    display: block;
    line-height: 24px;
  }
}
.header {
  height: 80px;
  width: 100%;
  background-color: #091b2f;
  .user {
    float: right;
    color: #fff;
    font-size: 14px;
    line-height: 30px;
    border: 1px solid #fff;
    border-radius: 5px;
    padding: 0 15px;
    margin-top: 7px;
  }
  .menu {
    float: right;
    font-size: 0;
    letter-spacing: -3px;
    margin-right: 50px;
    padding-top: 10px;
    li {
      display: inline-block;
      vertical-align: middle;
      letter-spacing: 0;
      font-size: 14px;
      width: 120px;
      text-align: center;
    }
  }
  .w {
    padding-top: 16px;
    .logo {
      background: url("../assets/logo.svg") no-repeat 0;
      width: 125px;
      height: 44px;
      display: block;
      float: left;
    }
  }
}
</style>
