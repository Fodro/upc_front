<template>
  <h1>{{myName}}</h1>
</template>

<script>
export default {
  name: "NameText",
  props: ['myName']
}

</script>

<style scoped>
@media not handheld {
  h1 {
    font-family: "Roboto Thin", sans-serif;
    font-size: 60px;
    margin-top: 20px;
    margin-left: 20px;
    color: #373d3e;
  }
}

@media screen and (orientation: portrait) {
  h1 {
    font-family: "Roboto Thin", sans-serif ;
    font-size: 57px;
    color: #373d3e;
    text-align: center;
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 86px;
  }
}
</style>
