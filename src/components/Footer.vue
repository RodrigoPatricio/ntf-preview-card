<template>
  <p class="line">______________________________________</p>
  <div class="footer">
    <img class="avatar" src="../assets/image-avatar.png" alt="" srcset="" />
    <p><span class="highlight"> Creation of</span> Jules Wyvern</p>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style>
.footer {
  max-width: 400px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
}
.footer p:hover {
  color: cyan;
}
.line {
  color: hsl(215, 32%, 27%);
  text-align: center;
  margin-bottom: 20px;
}
.avatar {
  width: 60px;
  border-radius: 50%;
  border: 2px solid white;
  margin-right: 10px;
}
.highlight {
  color: hsl(215, 51%, 70%);
}
</style>
