<template>
  <div id="intro"></div>
</template>

<script>
import dataJson from "@/assets/jyw.json";
export default {
  data() {
    return {
      src: null,
    };
  },
  created() {
    let url = "https://www.kinxpeng.com/demo/js/jyw/imgs/";
    let res = dataJson.data;
    console.log(res.nav);
  },
};
</script>

<style></style>
