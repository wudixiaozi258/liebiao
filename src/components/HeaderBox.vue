<template>
  <div class="header">
   <div class="headerBox">
    <div class="aa">
       <img src="https://img.js.design/assets/img/61405dfba781860684064243.png" alt="" class="a">
    </div>
    <div class="bb">
       <div class="b1"></div>
        <div class="b2"></div>
         <div class="b3"> </div>
          <div class="b4"></div>
    </div>
    <div class="cc">
       <div class="c1">我的订单</div>
        <div class="c2">我的评价</div>
         <div class="c3">收藏店铺 </div>
          <div class="c4">我的钱包</div>
    </div>
   </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderBox',
  props: {
    
  }
}
</script>

<style scoped lang="scss">
  .header{
    width: 375px;
    
    padding-left:25px ;
    padding-right:25px ;
  }
  .headerBox{
    height: 236px;
    border: 1px solid black;
    border-radius: 28px;
  }
  .aa{
    width:100%;
    height:124px;
  }
  .a{
    width:100%;
    height:124px;
    // border-radius
  }
  .bb{
    display: flex;
  }
  .b1{
    margin-left:30px;
    margin-top:26px;
     width:44px;
     height:44px;
     border-radius: 27.65px;
     background: rgba(255, 223, 117, 1);
  }
   .b2{
    margin-left:30px;
    margin-top:26px;
     width:44px;
     height:44px;
     border-radius: 27.65px;
     background: rgba(255, 223, 117, 1);
  }
   .b3{
    margin-left:30px;
    margin-top:26px;
     width:44px;
     height:44px;
     border-radius: 27.65px;
     background: rgba(255, 223, 117, 1);
  }
   .b4{
    margin-left:30px;
    margin-top:26px;
    margin-right:31px;
     width:44px;
     height:44px;
     border-radius: 27.65px;
     background: rgba(255, 223, 117, 1);
  }
  .cc{
    margin-top:12px;
    display:flex;
  }
  .c1{
     font-size:12px;
     font-weight: 500;
     margin-left:28px;
     margin-bottom:16px;
     width:48px;
     height:14px;
  }
  .c2{
font-size:12px;
     font-weight: 500;
     margin-left:25px;
     margin-bottom:16px;
      width:48px;
     height:14px;
  }
  .c3{
font-size:12px;
     font-weight: 500;
     margin-left:25px;
     margin-bottom:16px;
      width:48px;
     height:14px;
  }
  .c4{
font-size:12px;
     font-weight: 500;
     margin-left:25px;
     margin-bottom:16px;
      width:48px;
     height:14px;
  }
</style>
