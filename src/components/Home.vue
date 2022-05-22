<template>
  <b-container>
    <div style="padding: 20px 0 20px 0">
      <b-carousel
      fade
      indicators
      interval="4000"
      >
      <b-carousel-slide
      caption="英国"
      img-src="../assets/london.jpeg"
      style="max-height: 480px"
      ></b-carousel-slide>

      <b-carousel-slide
      caption="新加坡"
      img-src="../assets/singapore.jpeg"
      style="max-height: 480px"
      >
    </b-carousel-slide>

    <b-carousel-slide
    caption="德国"
    img-src="../assets/germany.jpeg"
    style="max-height: 480px"
    >
  </b-carousel-slide>

  <b-carousel-slide
  caption="澳大利亚"
  img-src="../assets/australia.jpeg"
  style="max-height: 480px"
  >
</b-carousel-slide>
</b-carousel>
</div>

<div style="padding: 20px 0 20px 0">
  <h3 class="text-center">关于我们</h3>
  <b-card
  img-src="../assets/logo.png"
  img-width="300"
  img-height="300"
  img-left
  style="border: none">
  <b-card-text>
    Hello Master是一家专注于硕士申请的线上服务平台。我们致力于通过数据，为同学们选择到最合适的海外院校。<br />
    我们运用最新爬虫技术，集合了英联邦国家各大高校的硕士申请数据。同学们可以根据自身情况，输入数据，快速选择出适合自己的院校。<br />
    同时，我们还提供基础的留学申请服务，为同学们的留学之旅，打开大门。
  </b-card-text>
</b-card>
</div>

<div style="padding: 20px 0 20px 0">
  <h3 class="text-center">我们的服务</h3>
  <b-card-group>
    <b-card
    title="择校"
    img-src="../assets/searching.png"
    img-height="200"
    img-top
    style="max-width: 30rem; border: none"
    >
    <b-card-text>
      我们运用最新爬虫技术，集合了英联邦国家各大高校的硕士申请数据。同学们可以根据自身情况，输入数据，快速选择出适合自己的院校。
    </b-card-text>
  </b-card>

  <b-card
  title="文书写作"
  img-src="../assets/writing.jpeg"
  img-height="200"
  img-top
  style="max-height: 10px; max-width: 30rem; border: none"
  >
  <b-card-text>
    专业文书老师量身书写你的Personal Statement
  </b-card-text>
</b-card>

<b-card
title="申请"
img-src="../assets/applying.png"
img-height="200"
img-top
style="max-height: 10px; max-width: 30rem; border: none"
>
<b-card-text>
  申请
</b-card-text>
</b-card>
</b-card-group>
</div>

<div style="padding: 20px 0 20px 0">
  <h3 class="text-center">为什么选择我们？</h3>
  专业
</div>

<div style="padding: 20px 0 20px 0">
  <h3 class="text-center">我们的宗旨</h3>
  <b-card style="border: none">
    <div class="text-center mb-4 pb-2">
      <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-quotes/bulb.webp"
      alt="Bulb" width="100">
    </div>

    <figure class="text-center mb-0">
      <blockquote class="blockquote">
        <p class="pb-3">
          <i class="fas fa-quote-left fa-xs text-primary"></i>
          <span class="lead font-italic">
            Work Hard, Play Hard
          </span>
          <i class="fas fa-quote-right fa-xs text-primary"></i>
        </p>
      </blockquote>
      <figcaption class="blockquote-footer mb-0">
        Imperial College London
      </figcaption>
    </figure>
  </b-card>
</div>

<footer class="text-center">
  陕西留梦咨询有限公司©2022
</footer>

</b-container>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null
    }
  },
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
