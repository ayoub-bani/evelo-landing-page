<template>
  <div>

      <div class="row">
        <div class="col">
          <section id="header" class="position-absolute">
            <div class="header-text position-relative text-white">
              <div class="container d-flex flex-column justify-content-center align-items-center">
                <!-- <h1 class="c-header-styles text-uppercase">Live life to the fulles?</h1>
                <p>Our electric bikes are specifically designed to give you the freedom to enjoy a more active and healthier lifestyle.</p> -->
              </div>
            </div>
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
      // width: 5rem;
    }
  }

</style>
