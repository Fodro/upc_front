<template>
  <div id="app" title="Hello, World!">
    <span>
      <NameText class="NameText" my-name="Tomilov Fedor"/>
      <JinguLogo class="JinguLogo"/>
    </span>
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
  span {
    display: flex;
    flex-direction: row;
  }
}

@media screen and (orientation: portrait){
  span {
    display: flex;
    flex-direction: column-reverse;
  }
}
</style>
