<!--  -->
<template>
  <div id="main">
    <Header title="喵喵影院"/>
    <Tabbar />
  </div>
</template>
 
<script>

import Header from '@/components/Header';
import Tabbar from '@/components/Tabbar';

export default {
  name: "cinema",
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