<template>
  <div>
    <!-- 模擬監看多台 server 的狀況 -->
    <app-server-status v-for="server in 5">Will be replaced by component template</app-server-status>
  </div>
</template>

<script>
import ServerStatus from "./ServerStatus.vue";

export default {
  components: {
    // 註冊 local components
    "app-server-status": ServerStatus
  }
};
</script>

<style>
</style>
