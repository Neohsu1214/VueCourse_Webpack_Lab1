<template>
  <!-- template 下面只可以有一個 root component，所以必須用一個 div 包起來 -->
  <div>
    <h1>Hello World! Status: {{ status }}</h1>
    <hr />
    <button @click="changeStatus">Change Status</button>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      status: "Critical"
    };
  },
  methods: {
    changeStatus: function() {
      this.status = "Normal";
    }
  }
};
</script>

<style>
</style>
