<template>
<div>
  <section class="section pt-0">
    <div class="container-fluid">
      <div class="row">
        <div class="col col-12">
          <div id="knx-slider" class="slick-slider gallery gallery--images gallery--carousel"> 
          <client-only>
            <slick :options="slickOptions">
              <div
                v-for="(image, index) in images"
                ref="slick"
                :key="'image-' + index"
                class="gallery__item"
              >
                <img class="gallery__image" :src="image.img" />
              </div>
            </slick>
          </client-only>
          </div>
        </div>
      </div>
    </div>
  </section>
  </div>
</template>

<script>
export default {
    data: () => ({
    slickOptions: {
      arows: false,
      dots: false,
      rows: 0,
      slidesToShow: 3,
      centerMode: true,
      variableWidth: false,
      responsive: [
        {
          breakpoint: 1024,
          settings: {
            slidesToShow: 1,
            infinite: true,
            dots: true
          }
        },
        {
          breakpoint: 600,
          settings: {
            slidesToShow: 1,
            width: 100
          }
        },
        {
          breakpoint: 480,
          settings: {
            slidesToShow: 1
          }
        }
        // You can unslick at a given breakpoint now by adding:
        // settings: "unslick"
        // instead of a settings object
      ]
    },
    images: [
      {
        img: require('~/assets/img/knx_img1.jpg')
      },
      {
        img: require('~/assets/img/knx_img2.jpg')
      },
      {
        img: require('~/assets/img/knx_img3.jpg')
      },
      {
        img: require('~/assets/img/knx_img4.jpg')
      },
    ]
  })
}
</script>

<style lang="scss"  scoped>
@import "~bootstrap/scss/bootstrap";
.gallery {
  .slick-list {
    overflow: visible;
  }

  &__item {
    white-space: normal;
    display: inline-block;
    vertical-align: top;
    transition: all .4s ease;
  }

  &--carousel {
    .gallery__item {
      max-width: 100%;
      overflow-x: hidden;
      //cursor: pointer;
      margin: 11px 15px 0 10px;

      opacity: 0.1;

      &:hover {
        transform: translateY(-8px);
      }

      //&[data-slick-index="-1"],
      //&[data-slick-index="3"]{
      //  opacity: .1;
      //}

      &.slick-active {
        opacity: 1;
      }
    }
  }

  &--images {
    width: initial !important;
    .gallery__item {
      height: 280px;

      @include media-breakpoint-down(md) {
        height: 230px;
      }

      @include media-breakpoint-down(sm) {
        height: 180px;
      }

      > .gallery__image {
        height: 100%;
        border-radius: 8px;
        background-size: cover;
        background-position: center center;
      }
    }
  }
}

</style>
