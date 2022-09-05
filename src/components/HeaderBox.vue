<template>
  <div class="header">
    <div class="headerBox">
      <span></span>
      <p>爱剁手的饼饼</p>
    </div>
    <div class="fourBox">
      <div>
        <div><img src="../../img/one.png" alt="" /></div>
        <span>我的订单</span>
      </div>
      <div>
        <div><img src="../../img/two.png" alt="" /></div>
        <span>我的评价</span>
      </div>
      <div>
        <div><img src="../../img/three.png" alt="" /></div>
        <span>收藏店铺</span>
      </div>
      <div>
        <div><img src="../../img/four.png" alt="" /></div>
        <span>我的钱包</span>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "HeaderBox",
  props: {},
};
</script>


<style scoped lang="scss">
.header {
  width: 326px;
  height: 236px;
  border-radius: 28px;
  // border: 1px solid red;
  margin: 0 auto;
  background: rgba(255, 255, 255, 1);
  .headerBox {
    // border: 1px solid black;
    border: none;
    border-radius: 28px;
    width: 326px;
    height: 124px;
    background: url("../../img/background.png") no-repeat;
    background-size: 326px 124px;
    span {
      display: inline-block;
      width: 48px;
      height: 48px;
      // margin-top: 28px;
      margin: 28px 0 0 139px;
      background: url("../../img/头像.png");
      background-size: 48px 48px;
    }
    p {
      text-align: center;
      text-shadow: 0px 2px 4px 0px rgba(0, 0, 0, 0.18);
      font-size: 12px;
      font-weight: 700;
      margin-top: 13px;
      color: rgba(255, 255, 255, 1);
    }
  }
  .fourBox {
    padding-top: 27px;


    height: 113px;
    width: 326px;
    display: flex;
    flex-direction: row;
    div {
      padding-left: 20px;
      flex: 1;
      div {
        padding-left: 2px;
        // margin-bottom: 12px;
        width: 44px;
        height: 44px;


        background: url("../../img/yellow.png");
        background-size: 44px 44px;
        img {
          width: 20px;
          height: 19px;
          display: inline-block;
          margin-left: 11px;
          margin-top: 13px;
          // border: 1px solid red;
          margin-bottom: 10px;
          // :nth-child(1) {
          //   z-index: 10;
          //   background: url("../../img/one.png");
          //   background-size: 19.5px 19.29px;
          // }
        }
      }
      span {
        font-size: 12px;
        font-weight: 500;
        letter-spacing: 0px;
        line-height: 0px;
        color: rgba(26, 26, 26, 1);
      }
    }
  }
}
</style>