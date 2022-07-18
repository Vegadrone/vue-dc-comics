<template>
  <div class="wrapper">
    <div class="container">
      <div class="row">
        <div class="col-12" v-for="(img, index) in imgList" :key="index">
            <img src="require(`../assets/img/buy-${img.imgPath}`)" alt="img.alt">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      imgList: [
        {
          imgPath: "comics-digital-comics.png",
          alt: "digital-comics.png",
        },
        {
          imgPath: "comics-merchandise.png",
          alt: "merchandise.png",
        },
        {
          imgPath: "comics-shop-locator.png",
          alt: "shop-locator.png",
        },
        {
          imgPath: "comics-subscriptions.png",
          alt: "subscriptions.png",
        },
        {
          imgPath: "dc-power-visa.svg",
          alt: "dc-power-visa.svg",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

.wrapper {
  background-color: $brandColor;
  height: 15rem;
}
</style>