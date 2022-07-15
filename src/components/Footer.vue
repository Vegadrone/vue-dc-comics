<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-3 d-flex">
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
        background-image: url(../assets/img/dc-logo-bg.png), url(../assets/img/footer-bg.jpg);
        background-position: right bottom, left top;
        background-repeat: no-repeat, repeat;
    }

    ul{
        list-style: none;
    }

</style>