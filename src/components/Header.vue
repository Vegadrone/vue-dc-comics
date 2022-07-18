<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="d-flex justify-content-around">
            <img src="../assets/img/dc-logo.png" alt="DC-logo" />
            <NavBar />
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import NavBar from "./NavBar.vue";

export default {
  name: "Header",
  components: {
    NavBar,
  },
};
</script>

<style lang="scss">
@import "../styles/variables.scss";

img {
  height: 4rem;
}
</style>