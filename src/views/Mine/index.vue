<!--  -->
<template>
  <div id="main">
    <Header title="我的影院" />
    <div id="content">
      <login />
    </div>
    <Tabbar />
  </div>
</template>
 
<script>
import Header from "@/components/Header";
import Tabbar from "@/components/Tabbar";
import Login from "@/components/Login";

export default {
  name: "mine",
  data() {
    return {};
  },

  components: {
    Header,
    Tabbar,
    Login
  }
};
</script>
<style lang='scss' scoped>
</style>