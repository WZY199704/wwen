<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!--    <Demo/>-->
    <!--    <m-card-->
    <!--      img-src="/java.png"-->
    <!--      summary="剑指Java面试—Offer直通车  百度资深面试官授课"-->
    <!--    />-->
    <!--    <m-card-->
    <!--      img-src="/c.png"-->
    <!--      summary="C语言系统化精讲  重塑你的编程思维 打造坚实的开发基础"-->
    <!--    >-->
    <!--      <template v-slot:footer>-->
    <!--        <div class="footer">-->
    <!--          <div class="level">中级 · 1337人报名</div>-->
    <!--          <div class="price">¥299.00</div>-->
    <!--        </div>-->
    <!--      </template>-->
    <!--    </m-card>-->
    <!--    <br>-->
    <m-card
            img-src="/images/test.jpeg"
            :width="270"
            :img-height="152"
    >
      李寻欢，古龙武侠小说《多情剑客无情剑》及其衍生作品中的第一男主角。
      <template v-slot:footer>
        <div class="footer-spring">
          <div class="level">多情剑客无情剑</div>
          <div class="level"></div>
        </div>
      </template>
    </m-card>
  </div>
</template>

<script>

  export default {
    name: 'App'
  }
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
