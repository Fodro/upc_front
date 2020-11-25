<template>
  <p>&#128563;</p>
</template>

<script>
export default {
  name: "Emoji"
}
</script>

<style scoped>
@media not handheld {
  p {
    margin-top: 0;
    font-size: 80px;
    animation-name: move;
    animation-duration: 10s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
  }
  @keyframes move {
    from {
      margin-left: 0%;
      width: 100%;
    }

    to {
      margin-left: 94%;
      width: 100%;
    }
  }
}
@media screen and (orientation: portrait) {
  p {
    margin-top: 80px;
    font-size: 80px;
    animation-name: move;
    animation-duration: 5s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
  }
  @keyframes move {
    from {
      margin-left: 0%;
      width: 100%;
    }

    to {
      margin-left: 78%;
      width: 100%;
    }
  }
}
</style>
