<template>
  <div class="section" id="carousel">
    <div id="carousel" class="container">

      <div class="row justify-content-center">
        <div style="width: 100%;">
          <el-carousel class="sliderContainer">
            <el-carousel-item class="slider">
              <img id="img1" class="d-block" alt="First slide" />
              <div class="carousel-caption d-none d-md-block">
              </div>
            </el-carousel-item>
            <el-carousel-item class="slider">
              <img id="img2" class="d-block" alt="Second slide" />
              <div class="carousel-caption d-none d-md-block">
              </div>
            </el-carousel-item>
            <el-carousel-item class="slider">
              <img id="img3" class="d-block" alt="Third slide" />
              <div class="carousel-caption d-none d-md-block">
              </div>
            </el-carousel-item>
          </el-carousel>

        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Carousel, CarouselItem } from 'element-ui';


export default {
  components: {
    [Carousel.name]: Carousel,
    [CarouselItem.name]: CarouselItem
  }
};
</script>
<style>
#carousel {
  max-width: 100%;
  padding: 5px 0px 0px 0px !important;
}

.slider {
  width: 100%;
}

el-carousel {
  height: 100%;
}



@media screen and (min-width: 1200px) {
  .slider {
    height: calc(100vw / 2.8) !important;
    overflow: visible;
  }

  .sliderContainer .el-carousel__container {
    height: calc(100vw / 2.8) !important;
    overflow: hidden;
  }

  .sliderContainer .el-carousel__container {
    height: calc(100vw / 2.8) !important;
    overflow: hidden;
  }

  #img1 {
    content: url("/img/banners/Banner1_rectangle.png");
  }

  #img2 {
    content: url("/img/banners/Banner2_rectangle.png");
  }

  #img3 {
    content: url("/img/banners/Banner3_rectangle.png");
  }

}




@media screen and (max-width: 1199px) {
  .slider {
    height: calc(100vw) !important;
    overflow: hidden;
  }

  .sliderContainer .el-carousel__container {
    height: calc(96vw) !important;
    overflow: hidden;
  }

  #img1 {
    content: url("/img/banners/Banner1_square.png");
  }

  #img2 {
    content: url("/img/banners/Banner2_square.png");

  }

  #img3 {
    content: url("/img/banners/Banner3_square.png");
  }

  .row{
    margin-left: 0!important;
    margin-right: 0!important;
  }

}
</style>
