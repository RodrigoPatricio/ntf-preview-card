<template>
  <div class="container">
    <Equilibrium />
    <Info />
    <Footer />
  </div>
</template>

<script>
import Equilibrium from "./components/Equilibrium";
import Info from "./components/Info";
import Footer from './components/Footer'

export default {
  name: "app",
  components: {
    Equilibrium,
    Info,
    Footer
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  cursor: pointer;
  font-family: outfit;
  background-color: hsl(217, 54%, 11%);
}
.container {
  background-color: hsl(216, 50%, 16%);
  color: white;
  max-width: 500px;
  margin: 100px auto;
  overflow: auto;
  min-height: 775px;
  padding: 30px;
  border-radius: 15px;
}

</style>
