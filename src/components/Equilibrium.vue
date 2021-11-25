<template>
  <div class="img-ntf">
    <img class="img" src="../assets/image-equilibrium.jpg" alt="" />
    <div class="middle">
      <img src="../assets/icon-view.svg" alt="">
    </div>
  </div>
  <div>
    <h3>{{ name }}</h3>
    <p class="description">{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "Equilibrium",
  data() {
    return {
      name: "Equilibrium #3429",
      text: "Our Equilibrium collection promotes balance and calm",
    };
  },
};
</script>

<style>
.img-ntf:hover .img {
  opacity: 0.3;
}
.img-ntf:hover .middle {
  opacity: 1;
}
.img {
  width: 400px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 15px auto 30px auto;
  border-radius: 15px;
  transition: .5s ease;
  backface-visibility: hidden;
}
.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 27%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}
h3{
    max-width: 400px;
    margin: auto;
    font-size: 30px;
    margin-bottom: 25px;
}
h3:hover {
  color: cyan;
}
.description {
    font-size: 22px;
    color: white;
    max-width: 400px;
    margin: auto;
    color: hsl(215, 51%, 70%);
    margin-bottom: 15px;
}
</style>
