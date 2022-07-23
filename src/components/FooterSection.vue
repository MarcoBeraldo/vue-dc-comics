<template>
  <div id="footer">
    <div class="container">
      <div class="upper-footer">

        <div class="dc-comics-list">
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#">Characters</a></li>      
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>

          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>      
          </ul>
        </div>        

        <div class="dc-list">
          <h3>DC</h3>
          <ul>
            <li><a href="#">Terms Of Use</a></li>      
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div class="sites-list">
          <h3>SITES</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>      
            <li><a href="#">DC Universe</a></li>      
            <li><a href="#">DC Power Visa</a></li>   
          </ul>
        </div>

      </div>

    <div>
        
      
  </div>
  </div>    
  </div>
</template>

<script>
export default {
  name: "FooterSection",
    
}
</script>

<style scoped>
#footer{ 
  background-image: url(../assets/img/footer-bg.jpg);
  background-position: center;
  background-size: cover;

}

.container{
  position: relative;
  max-width: 1500px;
  margin: 0 auto;
  display: flex;
}

.upper-footer{
  display: flex;
  align-items: center;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-position: right;
  background-repeat: no-repeat;
  background-size: 500px;
  width: 100%;
  height:100%;
  padding: 30px 0;  
}

#footer h3{
  color: white;
  font-size: 1.3rem;
  margin: 20px 0;
}

#footer ul{
  list-style-type: none;
  margin-right: 40px;
  padding: 0;
}

#footer ul a{
 text-decoration: none;
 color: gray;
} 
 
</style>