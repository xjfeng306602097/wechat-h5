<template lang="html">
  <section class="content">
    <!--<div class="img-wrap" v-for="k in content">
      <img :src="k.imgSrc">
    </div>-->
    <div v-if="content != ''" class="img-wrap" v-html="content">
    </div>
  </section>

</template>

<script>
export default {
  computed:{
    content(){
      debugger
      return this.$store.state.detail.imagesContent.replace(/\<img/gi, '<img style="width:100%;height:auto"');
    }
  }
}
</script>

<style lang="less" scoped>
  .content {
    width: 100%;
    margin-top: 10px;
    border-top: 20px solid #F8FCFF;
    .img-wrap {
      min-width: 320px;
      max-width: 640px;
      overflow: hidden;

      img {
        display: block;
        width: 100% !important;
      }
    }
  }
</style>
