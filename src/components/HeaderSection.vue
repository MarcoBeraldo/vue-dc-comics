<template>
  <section id="header">
    <div class="container">
        <div>

            <figure>
                <img src="../assets/img/dc-logo.png" alt="">
        </figure>
        <nav>
            <ul>
                <li><a v-for="(link, key) in data.data" 
                    v-bind:key="link.text" 
                    :href="link.url" 
                    :class="{current: link.current}"
                    @mouseover="setCurrent(key)">
                    {{ link.text }}</a></li>               
                
            </ul>
        </nav>
      </div>
    </div>
  </section>
</template>

<script>
import data from "../assets/data/data.js";
export default {
    name: "HeaderSection",
    data() {
   return {
    data,
   }},
   methods:{
    setCurrent(key){
        this.data.data[key].current === true;
    }
   }}

</script>

<style scoped>
#header{
    padding:10px;
}

.container{
    max-width: 1500px;
    margin: 0 auto;
}
.container>div{
    display:flex;
    justify-content: space-between;
    align-items: center;
}
ul{
    list-style-type: none;
    display: flex;
}

ul>li>a{
    color:black;
    text-decoration: none;
    margin: 0 20px;
    font-size: 0.9rem;
    font-weight: bold;
}
ul>li:hover>a.current{
    color: #0282F9;
}
</style>