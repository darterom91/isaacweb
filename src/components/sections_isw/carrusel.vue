<template>
  <div class="carrusel container-fluid rounded bg-warning opacity-75 p-0">
    <div
      id="carouselExampleControlsNoTouching"
      class="carousel slide carousel-fade"
      data-bs-touch="false"
      data-bs-interval="5000"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active" data-interval="2000">
          <img
            src="@/assets/img/ashley-smith-F7_SV8ZCPW8-unsplash.jpg"
            class="card-img w-100 opacity-75 "
            alt="..."
          />
          <div class="card-img-overlay">
            <h1
              class="card-title d-flex display-3 fw-bold text-dark h-100 align-items-center justify-content-center"
            >
              This is a wider card with supporting
            </h1>
            <p>Lorem ipsum dolor sit.</p>
          </div>
        </div>
        <div class="carousel-item" data-interval="2000">
          <img
            src="@/assets/img/ashley-smith-quR5WUxOxRA-unsplash.jpg"
            class="card-img w-100 opacity-75 "
            alt="..."
          />
          <div class="card-img-overlay">
            <h1
              class="card-title d-flex display-3 fw-bold text-dark h-100 align-items-center justify-content-center"
            >
              This is a wider card with supporting
            </h1>
            <p>Lorem ipsum dolor sit.</p>
          </div>
        </div>
        <div class="carousel-item" data-interval="2000">
          <img
            src="@/assets/img/mael-balland-n2S0h4S5KXY-unsplash.jpg"
            class="card-img w-100 opacity-75 "
            alt="..."
          />
          <div class="card-img-overlay">
            <h1
              class="card-title d-flex display-3 fw-bold text-dark h-100 align-items-center justify-content-center"
            >
              This is a wider card with supporting
            </h1>
            <p>Lorem ipsum dolor sit.</p>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleControlsNoTouching"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleControlsNoTouching"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
img{
  object-fit: cover;
  object-position: center;

  max-height: 500px;
  min-height: 300px;
}
</style>