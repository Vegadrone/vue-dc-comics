<template>
  <main>
    <img class="jumbotron" src="../assets/img/jumbotron.jpg" alt="Hero.img">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="wrapper d-flex  flex-wrap">
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
            <div class="comic-card">
              <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="comic">
              <h5>Action Comics</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang='scss'>
@import "../styles/variables.scss";
main {
  background-color: $bgColor;
}

.jumbotron{
  width: 100%;
  height: 50rem;
  object-fit: cover;
}

.wrapper{
  padding: 5rem;
}

.comic-card{
  width: calc(100% / 6);
  height: 4rem;
  padding: 5rem;

    .comic-card.img{
      width: 100%;
    }
}

</style>