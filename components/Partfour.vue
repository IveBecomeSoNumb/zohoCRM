<!--
 * @Author: your name
 * @Date: 2019-12-16 12:58:44
 * @LastEditTime: 2019-12-16 22:27:10
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \homeaway\components\Parttwo.vue
 -->
<template>
<div class="four-full">
<b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      
      <b-carousel-slide
        caption="One"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
        img-src="https://picsum.photos/1024/480/?image=52"
      ></b-carousel-slide>

    
      <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
        <h1>Two</h1>
      </b-carousel-slide>

      <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=58">
      <h1>Three</h1></b-carousel-slide>

      
      <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block img-fluid w-100"
            width="1024"
            height="480"
            src="https://picsum.photos/1024/480/?image=55"
            alt="image slot"
          >
        </template>
        <h1>Four</h1>
      </b-carousel-slide>
      <b-carousel-slide caption="Five" img-blank img-alt="Blank image">
        
      </b-carousel-slide>
    </b-carousel>

    
  </div>
</template>

<script>

export default {
    name:'partfour',
     
    
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
}

</script>

<style scoped>
.four-full{
    padding:80px 0px 90px;
    width: 100%;
    background:#d6efff;
    text-align: center;

}
.el-carousel__item h3 {
    color: #475669;
    font-size: 18px;
    opacity: 0.75;
    line-height: 300px;
    margin: 0;
  }
  
  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
</style>