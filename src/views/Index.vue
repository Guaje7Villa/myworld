<template>
  <div class="main">
    <div class="head"></div>
    <Typer class="typerDiv"></Typer>
  </div>
</template>

<script>
import Typer from "../components/Typer.vue";

export default {
  data() {
    return {};
  },
  components: {
    Typer
  }
};
</script>

<style lang="stylus">
.main
  width 100%
  height 960px
  position relative
  background url('../assets/bg.jpg') no-repeat 100% 100%
  background-size 100% 100% !important
  -moz-background-size 100% 100% !important
  -webkit-background-size 100% 100% !important

.head
  width 300px
  height 300px
  border-radius 500px
  position absolute
  left 50%
  top 25%
  transform translate(-50%, -50%)
  background url('../assets/SNS-head-Pic.jpg') no-repeat 100% 100%
  background-size 100% 100% !important
  -moz-background-size 100% 100% !important
  -webkit-background-size 100% 100% !important

.typerDiv
  width 100%
  height 150px
  position absolute
  left 50%
  top 50%
  transform translate(-50%, -50%)
</style>



