<template>
  <div id="app" title="Hello, World!">
    <NameText class="NameText" my-name="Tomilov Fedor"/>
    <JinguLogo class="JinguLogo"/>
    <Emoji class="Emoji"/>
  </div>
</template>

<script>
import NameText from "@/components/NameText";
import JinguLogo from "@/components/JinguLogo";
import Emoji from "@/components/Emoji";

export default {
  name: 'App',
  components: {
    Emoji,
    JinguLogo,
    NameText
  }
}
</script>

<style>
@media not handheld {
  #app {
    color: #2c3e50;
  }

  .JinguLogo {
    display: inline-block;
    text-align: end;
    margin-left: 50px;
    padding: 0;
    margin-bottom: 0;
  }

  .NameText {
    display: inline-block;
    padding: 0;
    margin-bottom: 0;
    margin-left: 10px;
  }

  .Emoji {
    padding: 0;
    margin-top: 0;
    margin-left: 0px;
  }
}
@media screen and (max-device-width: 1080px) and (max-device-height: 2400px){
  #app {
    color: #2c3e50;
  }

  .JinguLogo {
    display: flex;
  }

  .NameText {
    display: flex;
  }

  .Emoji {
    display: flex;
  }
}
</style>
