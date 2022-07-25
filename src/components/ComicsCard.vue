<template>
    
       

        <figure >
            <img :src="comic.thumb" alt="">
            <figcaption>{{comic.series}}</figcaption>

        </figure>
        

</template>

<script>

export default {
    name: "ComicsCard",
    props:{
        comic: Object
    }
    }
</script>

<style scoped>

figure{
    width: calc(100% / 6);
    margin-top:30px;
}
img{
    height: 200px;
}
figcaption{
    display:block;
    font-size: 0.8rem;
    width: 50%;
}
</style>