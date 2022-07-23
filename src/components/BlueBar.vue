<template>
    <div id="blue-bar">
        
        <div class="container">
            <div>

                <figure>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <figcaption>
                        DIGITAL COMICS
                    </figcaption>
                </figure>
                <figure>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <figcaption>
                        DIGITAL COMICS
                    </figcaption>
                </figure>
                <figure>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <figcaption>
                        DIGITAL COMICS
                    </figcaption>
                </figure>
                <figure>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <figcaption>
                        DIGITAL COMICS
                    </figcaption>
                </figure>
                <figure>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <figcaption>
                        DIGITAL COMICS
                    </figcaption>
                </figure>

            </div>
        </div>
    </div>
        
</template>

<script>
export default {
 name: "BlueBar",
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
    height:100%
}

figcaption{
    color: white;
    font-size: 1rem;
    font-weight: bold;
    margin-left: 20px;
}
</style>