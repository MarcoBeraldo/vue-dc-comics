<template>
  <div id="main">
    <div class="jumbotron"></div>
    
        <h3 class="label">CURRENT SERIES</h3>
        <div class="content">
          <div class="container">
            <div class="gallery">
              <ComicsCard v-for="(comic,index) in comics" :key="index" :comic="comic" />
            </div>

          </div>
        </div>


  </div>
</template>

<script>
import comics from "../assets/data/dc-comics.json";
import ComicsCard from "../components/ComicsCard.vue";
export default {
    name: "MainSection",
    data(){
    return{
        comics,
    }
 },
    components: {
      ComicsCard,
    }    
}
</script>

<style scoped>
#main .content{
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    color:white;
    font-size: 30px;
    font-weight: bold;
    padding: 30px;
}
 .jumbotron{
  height: 600px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
 }

 .container{
  max-width: 1200px;
  margin: 0 auto;
 }

 h3.label{
  display:inline-block;
  position: absolute;
  bottom:550px;
  left: 250px;
  background-color: #0282F9;
  color: white;
  padding: 5px;
  font-size: 1.5rem;
 }

 .gallery{
    display: flex;
    flex-wrap: wrap;
}

</style>