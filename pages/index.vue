<template>
<div>
  <div style="width:100%; height:5px; background-color:#00E917;"></div>
  <div style="position: relative">
    <div style="background: no-repeat url(img/image-95.png); background-size: cover; position: absolute; top: 0px; left: 0px; z-index: -2; width: 100%; height: 100%;"/>
    <div class="darken-background" style="z-index: -1"/>
    <main-menu style="margin: 0 auto;"/>
    <header-one class="content-item"/>
  </div>
  <header-phone class="content-item"/>
  <news class="content-item"/>
  <careers class="content-item" />
  <video-component/>
  <footer-component class="content-item"/>
</div>

</template>
<script>
import MainMenu from '~/components/MainMenu.vue'
import HeaderOne from '~/components/HeaderOne.vue'
import News from '~/components/News.vue'
import HeaderPhone from '~/components/HeaderPhone.vue'
import Careers from '~/components/Careers.vue'
import VideoComponent from '~/components/VideoComponent.vue'
import FooterComponent from '~/components/FooterComponent.vue'



export default {
  components: {
    MainMenu,
    HeaderOne,
    News,
    HeaderPhone,
    Careers,
    VideoComponent,
    FooterComponent

  }
}
</script>

<style>
.content-item {
  margin: 0 auto;
  max-width:1335px;
}
</style>
