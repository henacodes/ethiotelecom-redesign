<div class="carousel w-full h-[15rem] relative z-10">
  <div id="slide1" class="carousel-item relative w-full">
    <!-- svelte-ignore a11y-missing-attribute -->
    <img src="/slider1.png" class="w-full object-cover" />
    <div
      class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2"
    >
      <a href="#slide4" class="btn btn-circle">❮</a>
      <a href="#slide2" class="btn btn-circle">❯</a>
    </div>
  </div>
  <div id="slide2" class="carousel-item relative w-full">
    <!-- svelte-ignore a11y-missing-attribute -->
    <img src="/slider2.png" class="w-full object-cover" />
    <div
      class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2"
    >
      <a href="#slide1" class="btn btn-circle">❮</a>
      <a href="#slide3" class="btn btn-circle">❯</a>
    </div>
  </div>
</div>

<style>
  img {
    background-color: #000;
  }
</style>
