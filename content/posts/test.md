+++
title = "Test Swiper"
+++

<style>
.carousel {
width: 100%;
max-width: 800px;
margin: 20px auto;
overflow: hidden;
position: relative;
}

.carousel-images {
display: flex;
transition: transform 0.5s ease-in-out;
}

.carousel-images img {
width: 100%;
max-width: 800px;
}

.carousel-button {
position: absolute;
top: 50%;
transform: translateY(-50%);
background-color: rgba(0, 0, 0, 0.5);
color: white;
border: none;
padding: 10px;
cursor: pointer;
}

.carousel-button.prev {
left: 10px;
}

.carousel-button.next {
right: 10px;
}
</style>

<div class="carousel">
  <button class="carousel-button prev" onclick="prevSlide()">&#10094;</button>
  <div class="carousel-images" id="carouselImages">
    <img src="img/slide1.jpg" alt="Slide 1">
    <img src="img/slide2.jpg" alt="Slide 2">
    <img src="img/slide3.jpg" alt="Slide 3">
  </div>
  <button class="carousel-button next" onclick="nextSlide()">&#10095;</button>
</div>

<script>
  let currentIndex = 0;

  function showSlide(index) {
    const slides = document.getElementById('carouselImages');
    const totalSlides = slides.children.length;

    if (index >= totalSlides) {
      currentIndex = 0;
    } else if (index < 0) {
      currentIndex = totalSlides - 1;
    } else {
      currentIndex = index;
    }

    const offset = -currentIndex * 100; // 各スライドの幅分移動
    slides.style.transform = 'translateX(' + offset + '%)';
  }

  function nextSlide() {
    showSlide(currentIndex + 1);
  }

  function prevSlide() {
    showSlide(currentIndex - 1);
  }
</script>
