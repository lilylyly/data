<template>
  <div class="prt-care box">
    <span class="category">党内关怀</span>
    <div class="handle cl">
      <h2>爱心柜员机 关爱信息速递</h2>
      <button class="donate btn">捐助</button>
      <button class="help btn">求助</button>
    </div>
    <ul class="news">
      <li class="news-item">[捐助] [群众] 资助金</li>
      <li class="news-item">[捐助] [XX社区党支部] 资助金</li>
      <li class="news-item">[捐助] [XX党群服务站党支部] 资助金</li>
      <li class="news-item">[捐助] [XX有限公司党支部] 书籍：为什...</li>
      <li class="news-item">[捐助] [XX社区党支部] 南方杂志</li>
      <li class="news-item">[捐助] [XX社区党支部] 杂志</li>
    </ul>
  </div>
</template>

<style scoped>
  @import "../common/reset.css";

  .box {
    box-sizing: border-box;
    border-width: 1px;
    border-style: solid;
    border-color: rgba(121, 121, 121, 1);
  }

  .prt-care {
    width: 362px;
    height: 296px;
    padding: 0 6px;
  }

  .handle {
    height: 24px;
    padding: 4px;
    border-bottom: 1px dashed #797979;
  }

  .handle h2 {
    float: left;
    margin-right: 18px;
  }

  .btn {
    width: 68px;
    height: 21px;
    box-sizing: border-box;
    border: 1px solid #169bd5;
    background-color: #169bd5;
    border-radius: 5px;
    color: #fff;
  }

  .news-item {
    font-size: 13px;
    margin: 2px 0;
  }
</style>
