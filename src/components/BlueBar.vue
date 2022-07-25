<template>
    <div id="blue-bar">
        
        <div class="container">
            <div>

                <figure v-for="(image, index) in blueBarImages" :key="index">
                    <img :src="image.src" :alt="image.text">
                    <figcaption>
                        {{ image.text }}
                    </figcaption>
                </figure>

            </div>
        </div>
    </div>
        
</template>

<script>
import blueBarImages from "../assets/data/blueBarImages.js";


export default {
 name: "BlueBar",
 data(){
    return{
        blueBarImages,
    }
 }
}
</script>

<style scoped>
#blue-bar{
    height: 200px;
    background-color: #0282F9;
    
}

.container{
    max-width: 1400px;
    margin: 0 auto;
}

.container>div{
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

figure{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    cursor: pointer;
}

figure>img{
    height:100%;
}

figcaption{
    color: white;
    font-size: 1rem;
    font-weight: bold;
    margin-left: 20px;
}
</style>