<template>

  
  <div id="app">
    
    <HeaderSection />
    <MainSection />
    <BlueBar />
    <FooterSection />
    <LowerFooter />
  </div>
    
</template>

<script>
  import HeaderSection from "./components/HeaderSection.vue";
  import MainSection from "./components/MainSection.vue";
  import BlueBar from "./components/BlueBar.vue";
  import FooterSection from "./components/FooterSection.vue";
  import LowerFooter from "./components/LowerFooter.vue";


export default {
  name:"App",
  components: {
    HeaderSection, 
    MainSection, 
    BlueBar,
    FooterSection,
    LowerFooter,
}}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
}
</style>
