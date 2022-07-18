<template>
  <nav>
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex justify-content-between align-items-center">
          <a class="text-light" href="#">Sign up now!</a>
          <ul class="d-flex align-items-center">
            <li><h4>Follow us</h4></li>
            <li><img src="../assets/img/footer-facebook.png" alt="facebook-logo"></li>
            <li><img src="../assets/img/footer-twitter.png" alt="twitter-logo"></li>
            <li><img src="../assets/img/footer-youtube.png" alt="youtube-logo"></li>
            <li><img src="../assets/img/footer-pinterest.png" alt="pinterest-logo"></li>
            <li><img src="../assets/img/footer-periscope.png" alt="periscope-logo"></li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
    @import "../styles/variables.scss";

    nav{
        background-color: $footerBgColor;
        padding: 2rem 0rem
    }

    ul{
        height: 100%;
        list-style: none;
        margin: 0;
    }
    

    li{
      display: inline-block;
    }
    
    img{
        height: 3rem;
        margin-right: 1.5rem;
    }

    a{
        border: 2px solid $brandColor;
        text-align: center;
        padding: 1rem;
    }

    a,
    h4{
        text-decoration: none;
        font-size: 1.8rem;
        text-transform: uppercase;
        font-weight: bold;
    }

    h4{
      color: $brandColor;
       margin: 0rem 2rem;
    }

    

</style>