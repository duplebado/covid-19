<template>
    <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
 
  >
    <b-carousel-slide
      caption="First slide"
      img-src="../assets/images.png"
      id="sizer"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Second Slide"
      img-src="../assets/download.png"
      id="sizer"

    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="../assets/download (1).png"
      id="sizer"

    ></b-carousel-slide>
  </b-carousel>
</div>
</template>

<script>
export default {
    name: 'Slider'
}
</script>

<style scoped>
#sizer{
    width: 900px;
    height: 400px;
}
</style>