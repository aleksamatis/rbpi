<template>
<div>
  <div class="green-br"></div>
  <div class="main-relative">
    <!--INLINE STYLE-->
    <div style="background: no-repeat url(img/image-95.png); background-size: cover; position: absolute; top: 0px; left: 0px; z-index: -2; width: 100%; height: 100%;"/>
    <div class="darken-background main-z-index"/>
    <main-menu class="main-margin"/>
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
.green-br {
  width:100%; 
  height:5px; 
  background-color:#00E917;
}
.main-z-index {
  z-index: -1
}
.main-relative {
  position: relative
}
.main-margin {
  margin: 0 auto;
}
.content-item {
  margin: 0 auto;
  max-width:1335px;
}
</style>
