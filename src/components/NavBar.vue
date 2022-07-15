<template>
  <nav>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <ul>
            <li class="fw-bold">Characters</li>
            <li class="fw-bold">Comics</li>
            <li class="fw-bold">Movies</li>
            <li class="fw-bold">Tv</li>
            <li class="fw-bold">Games</li>
            <li class="fw-bold">Collectibles</li>
            <li class="fw-bold">Videos</li>
            <li class="fw-bold">Fans</li>
            <li class="fw-bold">News</li>
            <li class="fw-bold">Shop</li>
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
}

li {
  display: inline-block;
  margin: 0rem 1rem;
  padding: 2rem 0rem;
  border: 3px solid transparent;
  font-size: 0.8;

  &:hover {
    color: $brandColor;
    cursor: pointer;
    border-bottom: 3px solid $brandColor;
  }
}
</style>