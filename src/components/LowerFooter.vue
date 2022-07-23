<template>
    <div id="lower-footer">
        <div class="container">
            <div role="button" class="sign-up-btn">SIGN-UP NOW!</div>

            <div class="social">
                <a href="#"><span>FOLLOW US</span></a>
                <figure class="icons">
                   <a href="#"> <img src="../assets/img/footer-facebook.png" alt=""></a>
                   <a href="#"> <img src="../assets/img/footer-twitter.png" alt=""></a>
                    
                   <a href="#"> <img src="../assets/img/footer-youtube.png" alt=""></a>
                   <a href="#"> <img src="../assets/img/footer-pinterest.png" alt=""></a>
                   <a href="#"> <img src="../assets/img/footer-periscope.png" alt=""></a>
                </figure>
            </div>
      
        </div>
    </div>
</template>

<script>
export default {
name: "LowerFooter",
}
</script>

<style scoped>
#lower-footer{
    height: 130px;
    background-color: #303030;
    
}

.container{
    height: 100%;
    max-width: 1500px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.sign-up-btn{
    border: 2px solid #0282F9;
    padding: 10px;
    font-weight: bold;
    font-size: 1.2rem;
    color: white;
}

.social{
    display: flex;
    align-items: center;
}
#lower-footer a{
    font-size: 1.5rem;
    color: #0282F9;
    font-weight: bold;
    text-decoration: none;
    margin-right: 20px;

}
</style>