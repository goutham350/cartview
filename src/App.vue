<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<script>
import UIkit from 'uikit';
import Icons from 'uikit/dist/js/uikit-icons';

UIkit.use(Icons);

export default {
    
}
</script>
<style lang="less">

@import "../node_modules/uikit/src/less/uikit.less";

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #050569;
}

#nav {
  background-color: rgb(47, 48, 48);
  height: 100%;
}

</style>
