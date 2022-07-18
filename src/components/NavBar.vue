<template>
  <nav>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <ul class="d-flex align-items-center">
            <li class="fw-bold"><span>Characters</span></li>
            <li class="fw-bold"><span>Comics</span></li>
            <li class="fw-bold"><span>Movies</span></li>
            <li class="fw-bold"><span>Tv</span></li>
            <li class="fw-bold"><span>Games</span></li>
            <li class="fw-bold"><span>Collectibles</span></li>
            <li class="fw-bold"><span>Videos</span></li>
            <li class="fw-bold"><span>Fans</span></li>
            <li class="fw-bold"><span>News</span></li>
            <li class="fw-bold"><span>Shop</span></li>
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

ul {
  list-style: none;
  height: 100%;
}

li {
  height: 100%;
  display: flex;
  align-items: center;
  margin: 2rem 0.5rem;
  border: 5px solid transparent;
  font-size: 0.8rem;
  text-transform: uppercase;

  &:hover {
    color: $brandColor;
    cursor: pointer;
    border-bottom: 5px solid $brandColor;
  }
}
</style>