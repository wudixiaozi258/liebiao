<template>
  <div class="listall">
    <div class="listTitle"><span>近期购买</span></div>
    <div class="listbox1">
      <div class="listImg"><img src="../images/蒙版分组 (12).png@2x.png" alt=""></div>
      <div class="listCon">
        <div class="aaa">klee kler复古T恤</div>
        <div class="bbb"><span>尺码：XL</span> <span style="margin-left:10px;">颜色：白</span></div>
        <div class="ccc">¥320</div>

      </div>
      <div class="listStu"><div>未收货</div></div>
    </div>
    <div class="listbox1">
      <div class="listImg"><img src="../images/蒙版分组 (12).png@2x.png" alt=""></div>
      <div class="listCon">
        <div class="aaa">klee kler复古T恤</div>
        <div class="bbb"><span>尺码：XL</span> <span style="margin-left:10px;">颜色：白</span></div>
        <div class="ccc">¥320</div>

      </div>
      <div class="listStu"><div>未收货</div></div>
    </div>
    <div class="listbox1">
      <div class="listImg"><img src="../images/蒙版分组 (12).png@2x.png" alt=""></div>
      <div class="listCon">
        <div class="aaa">klee kler复古T恤</div>
        <div class="bbb"><span>尺码：XL</span> <span style="margin-left:10px;">颜色：白</span></div>
        <div class="ccc">¥320</div>

      </div>
      <div class="listStu"><div>未收货</div></div>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: 'ListBox',
  props: {

  }
}
</script>
  
  <style scoped lang="scss">
  .listall {
    width: 375px;
    margin-top: 30px;
    padding-left: 25px;
    padding-right: 25px;
  }
  
  .listTitle {
    // margin-bottom: 20px;
  
    span {
      font-size: 14px;
      font-weight: 700;
    }
  }
  
  .listbox1 {
    margin-top: 20px;
    padding: 7px;
    width: 326px;
    height: 98px;
    opacity: 1;
    border-radius: 20px;
    background: rgba(255, 255, 255, 1);
    display: flex;
    justify-content: space-between;
  
    .listImg {
      width: 84px;
      height: 84px;
      opacity: 1;
      border-radius: 20px;
      background: rgba(247, 247, 247, 1);
  
      img {
        width: 84px;
        height: 84px;
      }
    }
  
    .listCon {
      margin-left: -40px;
  
      div {
        width: 120px;
        display: flex;
        flex-direction: row;
  
      }
  
      .aaa {
        margin-top: 8px;
        height: 14px;
        opacity: 1;
        /** 文本1 */
        font-size: 12px;
        font-weight: 700;
      }
  
      .bbb {
        margin-top: 12px;
        font-size: 10px;
        font-weight: 500;
        color: rgba(204, 204, 204, 1);
      }
  
      .ccc {
        margin-top: 14px;
        font-size: 14px;
        font-weight: 700;
      }
    }
  }
  .listStu{
    font-size: 12px;
font-weight: 700;
color: rgba(255, 168, 168, 1);
display: flex;
align-content: center;
justify-content: center;
div{
  display: flex;
    justify-content: space-between;
    align-items: center; 
}
  }
  </style>
  