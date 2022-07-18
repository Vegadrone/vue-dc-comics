<template>
  <div class="background">
    <div class="container">
      <div class="row d-flex">
        <div class="col d-flex align-items-center justify-content-center" v-for="(img, index) in imgList" :key="index">
            <img :src="require(`../assets/img/buy-${img.imgPath}`)" alt="img.alt">
            <h6 class="text-light text-uppercase">{{img.text}}</h6>
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
          text:"Digital Comics",
          alt: "digital-comics.png",
        },
        {
          imgPath: "comics-merchandise.png",
          text:"Dc merchandise",
          alt: "merchandise.png",
        },
        {
          imgPath: "comics-shop-locator.png",
          text:"Subscription",
          alt: "shop-locator.png",
        },
        {
          imgPath: "comics-subscriptions.png",
          text:"Comic shop locator",
          alt: "subscriptions.png",
        },
        {
          imgPath: "dc-power-visa.svg",
          text:"Dc power visa",
          alt: "dc-power-visa.svg",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

.background {
  background-color: $brandColor;
  padding: 3rem;
}

img{
    height: 4rem;
    width: 3rem;
    margin-right: 0.8rem;
}
</style>