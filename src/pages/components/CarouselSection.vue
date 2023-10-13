<template>
  <div class="section" id="carousel">
    <div id="carousel" class="container">

      <div class="row justify-content-center">
        <div class="col-12">
          <el-carousel style="height: calc(100vw / 2.8)!important; overflow: hidden;">
            <el-carousel-item style="height: calc(100vw / 2.69)!important;">
              <img  class="d-block" id="slider" src="img/slider-1.png" alt="First slide" />
              <div class="carousel-caption d-none d-md-block">
              </div>
            </el-carousel-item>
            <el-carousel-item style="height: calc(100vw / 2.69)!important;">
              <img class="d-block" id="slider" src="img/slider-2.png" alt="Second slide" />
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

#slider {
  width: 100%;
}

el-carousel {
  height: 100%;
}


</style>
