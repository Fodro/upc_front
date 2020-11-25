<template>
  <img src='../assets/logo.png' alt="Jingu logo">
</template>

<script>
export default {
  name: "JinguLogo"
}
</script>

<style scoped>
@media not handheld {
  img {
    width: 90px;
    height: 90px;
    margin-top: 13px;
    border-radius: 90px;
    margin-left: 100px;
  }
}
@media screen and (orientation: portrait) {
  img {
    width: 200px;
    height: 200px;
    margin-top: 70px;
    border-radius: 200px;
    margin-left: 100px;
  }
}
</style>
