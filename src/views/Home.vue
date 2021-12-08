<template>
  <div class="home">
    <p>test</p>
    <div class="bus-section">
      <ul class="title-block">
        <li><h4 class="search-route">搜尋路線</h4></li>
        <li><h4 class="search-station">搜尋站名</h4></li>
        <li><h4>定位及地址搜尋</h4></li>
      </ul>
      <ul class="input-block">
        <li><input type="text" placeholder="請輸入公車路線..." /></li>
        <li><input type="text" placeholder="請輸入站名..." /></li>
        <li><input type="button" />搜尋附近站牌</li>
      </ul>
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
    margin: 0 auto;
    padding: 6% 0 0 6%;
    background-image: url("../assets/img/bus.svg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 91vh;
    width: 89%;
    background-position: top;
    font-weight: bold;
    font-size: 30px;
    ul {
      display: flex;
      width: 100%;
      border: 1px solid pink;
      li {
        width: 100%;
        text-align: center;
        border: 1px solid pink;
      }
    }
    .input-block {
      margin-top: 6%;
    }
  }
}
</style>
