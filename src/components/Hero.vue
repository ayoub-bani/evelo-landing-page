<template>
  <div>
      <div class="">
        <section id="header" class="position-relative">
          <div class="header-text position-absolute text-white">
            <div class="container d-flex flex-column justify-content-center align-items-center">
              <!-- play btn -->
              <img class="position-absolute c-btn-position" src="@/assets/btn_02.png" alt="play video button">
              <p class="play-styles position-absolute">play Video</p>
              <!-- rectangle -->
              <img class="position-absolute rectangle-position" src="@/assets/rectangle_101.png" alt="rectangle shape">
            </div>
          </div>
          <!-- shop bike btn -->
          <img class="position-absolute c-position-shop" src="@/assets/shop.png" alt="shop bike button">
          <!-- rectangle -->
          <img class="position-absolute c-position-rectangle" src="@/assets/rectangle02.png" alt="rectangle">
        </section>
      </div>
  </div>
</template>

<script>
export default {

}

</script>

<style scoped lang="scss">
  #header {
    background-image: url('~@/assets/asoggetti.jpg');
    background-size: cover;
    height: 130vh;
    width: 100vw;
    margin-top: -10rem;
    z-index: -1;

    .header-text {
      top: 15rem;
    }

    .c-header-styles {
      font-family: 'Oswald', sans-serif;
      font-weight: 500;
      font-size: 5rem;
    }

    .c-btn-position {
      height: 6rem;
      left: 7rem;
      top: 2rem;
      cursor: pointer;
    }

    .play-styles {
      font-family: 'Oswald', sans-serif;
      transform: rotate(90deg);
      left: 5rem;
      top: 14rem;
      width: 10rem;
      letter-spacing: 5px;
    }

    .line-styles {
      width: 20rem;
      color: black;
      height: 10rem;
      transform: rotate(90deg);
    }

    .rectangle-position {
      height: 15rem;
      left: 9.7rem;
      top: 18rem;
      z-index: 5;
    }

    .c-position-shop {
      height: 7rem;
      right: 0rem;
      top: 95vh;
    }
    .c-position-rectangle {
      bottom: -2px;
      z-index: -1;
    }
  }

</style>
