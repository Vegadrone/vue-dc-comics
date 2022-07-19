<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-6">
          <div class="row">
            <div class="col-4">
              <div class="menu-voice">
                <h4>Dc comics</h4>
                <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">Tv</a></li>
                  <li><a href="#">Games</a></li>
                  <li><a href="#">Collectibles</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">Fans</a></li>
                  <li><a href="#">News</a></li>
                  <li><a href="#">Shop</a></li>
                </ul>
              </div>
              <div class="menu-voice">
                <h4>Shop</h4>
                <ul>
                  <li><a href="#">Shop DC</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="menu-voice">
                <h4>Dc</h4>
                <ul>
                  <li><a href="#">Term Of Use</a></li>
                  <li><a href="#">Privacy Policy(New)</a></li>
                  <li><a href="#">Ad Choices</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Jobs</a></li>
                  <li><a href="#">Subscriptions</a></li>
                  <li><a href="#">Talent Workshops</a></li>
                  <li><a href="#">CPSC Certificate</a> s</li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Us</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="menu-voice">
                <h4>Sites</h4>
                <ul>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Univers</a></li>
                  <li><a href="#">DC Power Visa</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="col-6">
          <img src="../assets/img/dc-logo-bg.png" alt="logo-dc" />
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
@import "../styles/variables.scss";
footer {
  background-image: url(../assets/img/footer-bg.jpg);
}

.container {
  padding: 3rem 0rem;
}

h4 {
  text-transform: uppercase;
  color: white;
  font-weight: 600;
}

ul {
  list-style: none;
  
  padding: 0;
}

a {
  text-decoration: none;
  color: $textMenuColor;
}
</style>