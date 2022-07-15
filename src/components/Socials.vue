<template>
  <nav>
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex justify-content-between">
          <a href="#">Sign up now!</a>
          <ul>
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
    }

    ul{
        list-style: none;
    }

    li{
        display: inline-block;
    }
    
    img{
        height: 3rem;
    }

    a{
        border: 2px solid $brandColor;
        vertical-align: middle;
        text-align: center;
        padding: 1rem;
    }

    a,
    h4{
        text-decoration: none;
        font-size: 1.8rem;
        text-transform: uppercase;
        color: white;
    }

    

</style>