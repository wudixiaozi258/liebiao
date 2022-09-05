<template>
  <div class="tabber">
    <div class="tabber-img">
      <img src="../assets/矩形 2.png" alt="" />
      <img src="../assets/分组 3.png" alt="" />
      <img src="../assets/分组 2.png" alt="" />
      <img src="../assets/分组 1.png" alt="" />
    </div>
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
  margin-left: 21px;
  margin-right: 21px;
  .tabber-img {
    width: 266.9px;
    height: 18px;
    display: flex;
    flex-direction: row;
    margin: 0 auto;
    margin-top: 23px;
    img {
      width: 18px;
      height: 18px;
      object-fit:none ;
      flex: 1;
    }
  }
}
</style>
  