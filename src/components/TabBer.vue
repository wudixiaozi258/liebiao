<template>
    <div class="tabber">
        <div><img src="" alt=""></div>
        <div>1</div>
        <div>1</div>
        <div>1</div>
    </div>
</template>
  
  <script>
export default {
    name: 'TabBer',
    props: {

    }
}
</script>
  
  <style scoped lang="scss">
  .tabber {
      position: fixed;
      bottom: 24px;
      width: 334px;
      height: 66px;
      border-radius: 50px;
      background: rgba(255, 255, 255, 1);
      border: 1px solid black;
      margin-left: 21px ;
      margin-right: 21px;
      display: flex;
      justify-content: space-around;
      // align-content: center;
      line-height: 66px;
  }
  </style>
  