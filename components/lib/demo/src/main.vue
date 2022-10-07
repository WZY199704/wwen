<template>
  <div class="box" :style="{width:width+'px',height:height+'px'}">
    <div>{{word}}</div>
  </div>
</template>

<script>
  export default {
    name: "Demo",
    props: {
      word: { // 内容
        type: String,
        default: ''
      },
      width: {
        type: Number,
        default: 0
      },
      height: {
        type: Number,
        default: 0
      }
    }
  }
</script>

<style scoped>

</style>
