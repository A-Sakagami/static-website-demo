+++
date = '2024-11-11T10:00:00+09:00'
draft = false
title = 'Carousel Sample'
[[images]]
src = "/img/slide1.jpg"
alt = "Person"

[[images]]
src = "/img/slide2.jpg"
alt = "Slide2"
caption = "AI chip"

[[images]]
src = "/img/slide3.jpg"
alt = "Slide3"
caption = "Fire Twitter bird"
+++

## カルーセルのサンプル

カルーセルとは：画像などの複数の項目をスライドさせることで、メインで表示する項目を切り替えることができる仕組み
引用：[DAC Solution Service:カルーセルとは](https://solutions.hakuhodody-one.co.jp/glossary/carousel-ad)
<body>
 <div>
   {{< swiper >}}

   <!-- Add Pagination -->
   <div class="swiper-pagination"></div>
   <div class="swiper-button-next"></div>
   <div class="swiper-button-prev"></div>
  </div>
</body>
