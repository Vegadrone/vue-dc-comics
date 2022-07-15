<template>
  <nav>
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex">
          <a href="">Sign up now!</a>
          <h4>Follow us</h4>
          <ul>
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

</style>