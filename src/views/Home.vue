<template>
  <div class="home">
    <div class="bus-section">
      <h4>搜尋路線</h4>
      <h4>搜尋站名</h4>
      <h4>定位及地址搜尋</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>

<style lang="scss" scoped>
.home {
  background-size: cover;
  background-image: url("../assets/img/bgImage.svg");
  min-height: 100vh;
  .bus-section {
    margin: 0 auto;
    background-image: url("../assets/img/bus.svg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 60%;
    width: 80%;
    background-position: top center;
  }
}
</style>
