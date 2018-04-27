<template>
  <div class="lf-service box">
    <span class="category">生活服务</span>
    <div class="type">
      <div class="type-item">
        <div class="img-box box">

        </div>
        <span>水费</span>
      </div>
      <div class="type-item">
        <div class="img-box box">

        </div>
        <span>电费</span>
      </div>
      <div class="type-item">
        <div class="img-box box">

        </div>
        <span>电话费</span>
      </div>
    </div>
  </div>
</template>

<style>
  @import "../common/reset.css";

  .box {
    box-sizing: border-box;
    border-width: 1px;
    border-style: solid;
    border-color: rgba(121, 121, 121, 1);
  }

  .lf-service {
    width: 362px;
    height: 107px;
    overflow: hidden;
    padding: 0 6px;
  }

  .type-item  {
    width: 58px;
    height: 80px;
    margin: 14px 12px 0;
    float: left;
  }

  .img-box {
    width: 58px;
    height: 49px;
  }

  .type-item span {
    font-size: 12px;
    text-align: center;
    line-height: 14px;
    margin: 0;
    width: 58px;
    display: inline-block;
  }
</style>
