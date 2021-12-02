<template>
  <div class="home">
    <p>test</p>
    <div class="bus-section">
      <h4 class="search-route">搜尋路線</h4>
      <h4 class="search-station">搜尋站名</h4>
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
  p {
    color: transparent;
    margin-bottom: 2%;
  }
  .bus-section {
    display: flex;
    margin: 0 auto;
    padding: 6% 0 0 30.5%;
    background-image: url("../assets/img/bus.svg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 91vh;
    width: 89%;
    background-position: top;
    font-weight: bold;
    font-size: 30px;
  }
  .search-route {
    margin-right: 18%;
  }
  .search-station {
    margin-right: 12.5%;
  }
}
</style>
