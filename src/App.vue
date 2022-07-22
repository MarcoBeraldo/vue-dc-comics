<template>

  
  <div id="app">
    
    <HeaderSection />
  </div>
    
</template>

<script>
  import HeaderSection from "./components/HeaderSection.vue";
export default {
  name:"App",
  components: {
    HeaderSection,
  
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
