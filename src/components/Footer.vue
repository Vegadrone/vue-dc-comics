<template>
  <footer>
    <div class="container">
      <div class="row d-flex">
        <div class="col-6 d-flex" >
          <h4>Dc comics</h4>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>Tv</li>
            <li>Games</li>
            <li>Collectibles</li>
            <li>Videos</li>
            <li>Fans</li>
            <li>News</li>
            <li>Shop</li>
          </ul>
          <h4>Shop</h4>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
          <h4>Dc</h4>
          <ul>
            <li>Term Of Use</li>
            <li>Privacy Policy(New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
          <h4>Sites</h4>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Univers</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <div class="col-6">
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
      </div>
    </div>
    <Socials />
  </footer>
</template>

<script>
import Socials from "./Socials.vue";

export default {
  name: "Footer",
  components: {
    Socials,
  },
};
</script>

<style lang="scss" scoped>
    footer{
        background-image:url(../assets/img/footer-bg.jpg);
    }

    .container{
      padding: 3rem 0rem
    }

    h4{
      text-transform: uppercase;
      color: white;
    }

    ul{
        list-style: none;
        color: white;
    }

</style>