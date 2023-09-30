<script>
  import Carousel from "./Carousel.svelte";
</script>

<div class="header pt-5">
  <div
    class="header-top z-20 relative flex items-center justify-between px-5 pb-5"
  >
    <div>
      <img src="/tele.png" class="w-[10rem]" alt="" />
    </div>
    <div class="flex items-center">
      <div class="form-control mr-5">
        <label class="label cursor-pointer">
          <span class="label-text mx-3">Amharic</span>
          <input type="checkbox" class="toggle toggle-primary" checked />
          <span class="label-text mx-3">English</span>
        </label>
      </div>
      <img src="/menu.svg" alt="" />
    </div>
  </div>
  <Carousel />
</div>
