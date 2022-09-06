<template>

    <div class="tabber">
        <div><img src="../images/矩形 2@2x.png" alt=""></div>
        <div><img src="../images/分组 1@2x.png" alt=""></div>
        <div><img src="../images/分组 3@2x.png" alt=""></div>
        <div><img src="../images/并集@2x.png" alt=""></div>

    </div>

</template>
  
  <script>
export default {
  name: "TabBer",
  props: {},
};
</script>
  
  <style scoped lang="scss">
  .tabber {
      position: fixed;
      bottom: 24px;
      width: 334px;
      height: 66px;
      border-radius: 50px;
      background: rgba(255, 255, 255, 1);
      margin-left: 21px ;
      margin-right: 21px;
      display: flex;
      justify-content: space-around;
      align-content: center;
      // line-height: 66px;
      div{
        display: flex;
            /* 针对子元素的垂直方向对齐方式 */
            align-items: center; 
            /* 对子元素的水平方向对齐方式 */
            justify-content: center;
      }
      img{
        width: 18px;
        height: 18px;
      }

  }
}
</style>
  