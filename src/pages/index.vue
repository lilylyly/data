<template>
  <div class="left">
    <mheader></mheader>
    <service></service>
    <prtcare></prtcare>
  </div>
</template>

<script>
  import mheader from '../components/head.vue'
  import service from '../components/service.vue'
  import prtcare from '../components/prtcare.vue'

  export default {
    components: {
      mheader,
      service,
      prtcare,
    }
  }
</script>

<style scoped>
  @import "../common/reset.css";
  .left {
    width: 362px;
  }
</style>
