<template>

  
  <div id="app">
    
    <HeaderSection />
    <MainSection />
    <BlueBar/>
  </div>
    
</template>

<script>
  import HeaderSection from "./components/HeaderSection.vue";
  import MainSection from "./components/MainSection.vue";
  import BlueBar from "./components/BlueBar.vue";
export default {
  name:"App",
  components: {
    HeaderSection, 
    MainSection, 
    BlueBar,
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
