<!--  -->
<template>
  <div id="main">
    <Header title="我的影院"/>
    <Tabbar />
  </div>
</template>
 
<script>

import Header from '@/components/Header';
import Tabbar from '@/components/Tabbar';

export default {
  name: "mine",
  data() {
    return {};
  },

  components: {
    Header,
    Tabbar
  }
};
</script>
<style lang='scss' scoped>
</style>