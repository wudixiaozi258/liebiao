<template>
  <div id="app">
    <HeaderBox/>
    <ListBox/>
    <TabBer/>
  </div>
</template>
<script>
  import HeaderBox from "./components/HeaderBox.vue";
  import ListBox from "./components/ListBox.vue";
  import TabBer from "./components/TabBer.vue"
  export default {
  components: {
    HeaderBox,
    ListBox,
    TabBer
  },
};
</script>
<style lang="scss">
*{
  padding: 0;
  box-sizing: border-box;
  margin: 0;

}
#app{
  height: 2000px;
  padding-top: 20px;
  background-color: #f7f7fa;
}
</style>
