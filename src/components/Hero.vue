<template>
  <div>

    <div class="row">
      <div class="">
        <section id="header" class="position-relative">
          <div class="header-text position-absolute text-white">
            <div class="container d-flex flex-column justify-content-center align-items-center">
              <!-- play btn -->
              <img class="position-absolute c-btn-position" src="@/assets/btn_02.png" alt="play video button">
              <p class="play-styles position-absolute">play Video</p>
              <!-- rectangle -->
              <img class="position-absolute rectangle-position" src="@/assets/rectangle.png" alt="rectangle shape">
            </div>
          </div>
          <!-- shop bike btn -->
          <img class="position-absolute c-position-shop" src="@/assets/shop.png" alt="shop bike button">
        </section>
      </div>
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
      left: 15rem;
      top: 2rem;
      cursor: pointer;
    }

    .play-styles {
      font-family: 'Oswald', sans-serif;
      transform: rotate(90deg);
      left: 13rem;
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
      left: 17.5rem;
      top: 18rem;
    }

    .c-position-shop {
      height: 7rem;
      right: 0rem;
      top: 95vh;
    }
  }

</style>
