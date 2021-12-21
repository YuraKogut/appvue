<template>
  <div id="app">
    <appHeader />
  <router-view/>
   <appSideBar />
   <appFooter />
    
  </div>
</template>

<script>
import appHeader from '@/components/header.vue';
import appSideBar from '@/components/side-bar.vue';
import appFooter from '@/components/footer.vue';
  export default {
    components:{
      appHeader,appSideBar,appFooter,
    }
  };
</script>

<style lang="scss" scoped>

</style>
