<template>
  <div class="container">
      <div id="head" class="box">
        <div class="title cl">
          <div class="logo">
            <img src="../assets/img/u281.png">
          </div>
          <h1>汇川区党建大数据平台</h1>
        </div>
        <div class="user">
          <span>用户名</span>
          <input id="user_name" type="text" placeholder="登录ID/身份证号">
        </div>
        <div class="pass">
          <span>密码</span>
          <input id="pass_word" type="text" placeholder="登录ID/身份证号">
        </div>
        <button class="login">登陆</button>
      </div>
      <div class="leaderboard box">
        <div class="title cl">
          <img src="../assets/img/u284.png" alt="" class="star_icon">
          <h2>"双晋"排行榜</h2>
          <img src="../assets/img/u284.png" alt="" class="star_icon">
        </div>
        <span class="category">支部晋级</span>
        <table>
          <thead>
          <tr>
            <th width="48px">名次</th>
            <th width="192px">名称</th>
            <th width="48px">积分</th>
          </tr>
          </thead>
          <tbody>
          <tr>
            <td>1</td>
            <td>中坝村党支部</td>
            <td>150</td>
          </tr>
          <tr>
            <td>2</td>
            <td>乐遥村党支部</td>
            <td>150</td>
          </tr>
          <tr>
            <td>3</td>
            <td> </td>
            <td>150</td>
          </tr>
          </tbody>
        </table>
        <span class="category">党员晋星</span>
        <table>
          <thead>
          <tr>
            <th width="48px">名次</th>
            <th width="48px">姓名</th>
            <th width="144px">党支部</th>
            <th width="48px">积分</th>
          </tr>
          </thead>
          <tbody>
          <tr>
            <td>1</td>
            <td>张岳云</td>
            <td>中坝村党支部</td>
            <td>150</td>
          </tr>
          <tr>
            <td>2</td>
            <td>张爱兰</td>
            <td>乐遥村党支部</td>
            <td>150</td>
          </tr>
          <tr>
            <td>3</td>
            <td> </td>
            <td> </td>
            <td>150</td>
          </tr>
          </tbody>
        </table>
        <span class="more">更多>></span>
      </div>
  </div>
</template>

<script>

</script>

<style scoped>
  @import "../common/reset.css";
  .left {
    width: 362px;
    float: left;
  }
  .box {
    box-sizing: border-box;
    border-width: 1px;
    border-style: solid;
    border-color: rgba(121, 121, 121, 1);
  }

  #head {
    width: 362px;
    height: 104px;
    padding: 4px 10px 0;
  }

  .title  {
    margin-bottom: 20px;
  }

  .logo {
    width: 44px;
    height: 46px;
    float: left;
  }

  .logo img {
    width: 44px;
    height: 46px;
  }

  #head h1 {
    font-family: 'PingFangSC-Regular', 'PingFang SC';
    font-weight: 400;
    line-height: 46px;
    font-style: normal;
    font-size: 20px;
    color: #1E1E1E;
    margin-left: 27px;
    float: left;
  }

  span {
    font-size: 13px;
    margin-right: 6px;
  }

  .user {
    float: left;
    margin-right: 12px;
  }

  #head input {
    font-family: 'ArialMT', 'Arial';
    font-weight: 400;
    font-style: normal;
    font-size: 10px;
  }

  #user_name {
    width: 87px;
    height: 19px;
  }

  .pass {
    float: left;
    margin-right: 12px;
  }

  #pass_word {
    width: 70px;
    height: 19px;
  }

  .login {
    width: 52px;
    height: 26px;
    box-sizing: border-box;
    border-width: 1px;
    border-style: solid;
    border-color: rgba(121, 121, 121, 1);
    border-radius: 5px;
    background: transparent;
  }

  .leaderboard {
    width: 362px;
    height: 334px;
    font-weight: 400;
    font-style: normal;
    font-size: 14px;
    padding: 0 20px;
  }

  .star_icon {
    float: left;
    display: inline-block;
    margin-right: 20px;
    padding-top: 4px;
  }

  .leaderboard h2 {
    width: 112px;
    font-weight: 400;
    font-style: normal;
    font-size: 16px;
    float: left;
  }

  .leaderboard .title {
    width: 185px;
    margin: 10px auto 0;
  }

  table {
    margin-left: 20px;
    margin-bottom: 20px;
  }

  thead tr {
    border-top: 1px solid #797979;
  }

  tbody {
    border-top: 4px solid #fff;
  }

  th {
    height: 25px;
    line-height: 25px;
    border-right: 1px solid #797979;
  }

  th:last-child {
    border: none;
  }

  td {
    text-align: center;
    height: 20px;
    line-height: 20px;
    border-right: 1px solid #797979;
  }

  td:last-child {
    border: none;
  }

  .more {
    float: right;
  }

</style>
