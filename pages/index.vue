<template>
  <div>
    <Vue-Slick-Carousel :arrows="true" :dots="true">
      <div>1</div>
      <div>2</div>
      <div>3</div>
      <div>4</div>
    </Vue-Slick-Carousel>
  </div>
</template>

<script>
import Header from "../components/Header";
import Footer from "../components/Footer";
export default {
  name:"IndexPage",
  components:{Header,Footer}
}
</script>
