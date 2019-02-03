<template>
  <div id="app">
    <CommonHeader siteName="template"/>
    <main>
      <router-view/>
    </main>
    <CommonFooter copy="vue-fire-template"/>
  </div>
</template>
<script>
import CommonHeader from "@/components/CommonHeader.vue";
import CommonFooter from "@/components/CommonFooter.vue";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>


<style lang="scss">
</style>
