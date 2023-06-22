<script>
import Appheader from './components/Appheader.vue';
import Appmain from './components/Appmain.vue';
import Appfooter from './components/Appfooter.vue';
export default {
  components: {
    Appheader,
    Appmain,
    Appfooter
  }
}
</script>
<template lang="">
  <div>
    <Appheader></Appheader>
    <Appmain></Appmain>
    <Appfooter></Appfooter>
  </div>
</template>

<style lang="scss">
@use './styles/general.scss' as*;
</style>