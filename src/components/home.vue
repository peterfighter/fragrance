<template>
  <div id="home">
    <div class="home-header">
      conceal fragrance
    </div>
    <div class="lump-gap"></div>
    <div class="text-content">
      <div class="content-height">I am the daughter of the</div>
      <div class="content-height">elements With whom Winter conceived; </div>
      <div class="content-height">To whom Spring gave birth;</div>
      <div class="content-height">I was Reared in the lap of Summer and </div>
      <div class="content-height">I Slept in the bed of Autumn.</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
  .home-header{
        height: 150px;
      text-align: center;
      line-height: 150px;
      font-family: fantasy;
      font-size: 46px;
      background-color: beige;
      min-width: 600px;
  }
  .lump-gap{
    height: 20px;
  }
  .text-content{
    text-align: center;
  }
  .content-height{
    height: 40px;
    line-height: 40px;
  }
</style>
