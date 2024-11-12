+++
date = '2024-11-11T10:00:00+09:00'
draft = false
title = 'Carousel Sample'
+++

## カルーセルのサンプル

カルーセルとは：画像などの複数の項目をスライドさせることで、メインで表示する項目を切り替えることができる仕組み
引用：[DAC Solution Service:カルーセルとは](https://solutions.hakuhodody-one.co.jp/glossary/carousel-ad)

<head>
  <style>
   .swiper-container {
    width: 100%;
    height: 400px;
    margin: 20px auto;
   }
  .swiper-slide {
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
   }
  </style>
</head>

<div class="swiper-container">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="/img/slide1.jpg" alt="Slide 1">
    </div>
    <div class="swiper-slide">
      <img src="/img/slide2.jpg" alt="Slide 2">
    </div>
    <div class="swiper-slide">
      <img src="/img/slide3.jpg" alt="Slide 3">
    </div>
  </div>
  <!-- Add Pagination -->
  <div class="swiper-pagination"></div>
  <!-- Add Navigation -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
</div>