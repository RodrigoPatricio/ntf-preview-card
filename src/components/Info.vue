<template>
  <div class="info">
      <div>
    <img class="img-info" src="../assets/icon-ethereum.svg" />
    <p class="price">{{ price }}</p>
    </div>
    <div>
        <img class="img-info" src="../assets/icon-clock.svg" alt="" srcset="">
        <p>{{ days }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Info",
  data() {
    return {
      price: "0.041 ETH",
      days: "3 days left",
    };
  },
};
</script>

<style>
.info div {
    margin-top: 20px;
    margin-bottom: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.price {
    color: cyan;
}
.info {
    max-width: 400px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: auto;
    font-size: 22px;

}

.img-info {
  height: 25px;
  margin-right: 10px;
}
</style>
