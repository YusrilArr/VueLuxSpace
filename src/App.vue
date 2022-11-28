<template>
  <div id="app">
   
    <NavbarComp></NavbarComp>
    <BreadcumbComp></BreadcumbComp>
    <ContentComp></ContentComp>
    <SliderComp></SliderComp>
    <FooterComp></FooterComp>
    <CopyrightComp></CopyrightComp>
  </div>
</template>

<script>
import NavbarComp from './components/NavbarComp.vue'
import BreadcumbComp from './components/BreadcumbComp.vue'
import ContentComp from './components/ContentComp.vue'
import SliderComp from './components/SliderComp.vue'
import FooterComp from './components/FooterComp.vue'
import CopyrightComp from './components/CopyrightComp.vue'
export default {
  name: 'App',
  components: {
    NavbarComp,
    BreadcumbComp,
    ContentComp,
    SliderComp,
    FooterComp,
    CopyrightComp
  }
}
</script>

<style>

</style>
