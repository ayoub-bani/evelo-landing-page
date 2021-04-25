<template>
  <div class="">
    <nav id="navbar" class="container d-flex justify-content-between p-5">
      <!-- Logo -->
      <div class="">
        <img class="c-logo-size" src="@/assets/evelo-logo.png" alt="evelo logo">
      </div>
      <!-- center Navbar -->
      <ul class="nav justify-content-center">
        <li class="nav-item">
          <a class="nav-link active text-uppercase text-dark" href="#">Bikes</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-uppercase text-dark" href="#">Accessories</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-uppercase text-dark" href="#">Reviews</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-uppercase text-dark" href="#">Service</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-uppercase text-dark" href="#">Contact</a>
        </li>
      </ul>
      <!-- shop icon -->
      <div class="justify-content-center">
        <img class="c-shop-icon-height mt-2" src="@/assets/shopping-bag.png" alt="shoping icon">
      </div>
    </nav>
  </div>
</template>

<script>
export default {}

</script>

<style scoped lang="scss">
#navbar {

  .c-logo-size {
    height: 3rem;
  }
  .c-shop-icon-height {
    height: 1rem;
  }

// link font family
  .nav-link {
    font-family: 'Oswald', sans-serif;
  }
}

</style>
