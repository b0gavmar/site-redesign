<script setup></script>

<template>
  <main>
    <div class="container-fluid hero-image">
      <div
        class="container d-flex align-items-center justify-content-center w-100 h-100"
      >
        <h1 class="text-dark display-4 fw-bold rounded p-2 glass-bg">
          Referenciák
        </h1>
      </div>
    </div>

    <div class="container container2 my-5">
      <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img
              src="https://s3.divcom.com/www.commercialuavnews.com/images/d065b8e0c4020e661d465ebe70c63726.jpg"
              class="d-block w-100"
              alt="Drón 1"
            />
          </div>
          <div class="carousel-item">
            <img
              src="https://asteria.co.in/public/assets/img/indus/agriculture/Header-Banner_1.jpg"
              class="d-block w-100"
              alt="Drón 2"
            />
          </div>
          <div class="carousel-item">
            <img
              src="https://grc-international.net/wp-content/uploads/2020/07/Use-Of-Drones.jpg"
              class="d-block w-100"
              alt="Drón 3"
            />
          </div>
        </div>

        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExample"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Előző</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExample"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Következő</span>
        </button>
      </div>
    </div>
  </main>
</template>

<style scoped>
.carousel-item img {
  max-height: 500px;
  height: 100%;
  object-fit: cover;
}
</style>
