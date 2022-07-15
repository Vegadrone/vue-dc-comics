<template>
  <header>
    <div class="d-flex justify-content-around">
      <img src="../assets/img/dc-logo.png" alt="DC-logo" />
      <NavBar />
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

    img{
        height: 5rem;
    }
</style>