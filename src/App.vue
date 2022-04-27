<script setup>
import {onMounted} from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundColor="#ffff"
  document.getElementsByTagName("body")[0].style.backgroundSize="cover";
});
</script>


  <header>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css">
  </header>
  <body>
  <!-- pembuka navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success bg-opacity-70 shadow">
    <div class="container">
      <a class="navbar-brand">
        <img src="/src/assets/logo.svg" alt="" width="50" height="34" class="d-inline-block align-text-top">
        <b>AIDIL ZIKRI</b>
      </a>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page"><b>APP <i class="bi bi-app"></i></b></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="src/home.vue">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="src/profil.vue">Profil</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="src/pekerjaan.vue">Kegiatan</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="src/about.vue">About</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- penutup navbar -->

  <p class="placeholder-glow">
    <span class="placeholder col-12"></span>
  </p>
  <h1 style="color: white" class="text-center pd-5">
    <span class="badge bg-secondary">ini halaman utama web</span>
  </h1>

  <p class="placeholder-wave">
    <span class="placeholder col-12"></span>
  </p>

  <section id="awal">
    <div class="container mt-5">
      <div class="row ms-5 justify-content-center">
        <div class="col-md-3 fs-3 text-dark ">
          <p>Selamat Datang di website saya. ini merupakan tampilan awal web</p>
        </div>
        <div class="col-md-9">
          <img src="src/assets/selamat.png" width="150"
          height="150">
        </div>
      </div>
    </div>
  </section>

  <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="../src/assets/laptop1.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="../src/assets/laptop2.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="../src/assets/laptop3.jpg" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  <nav aria-label="Page navigation example" class="mt-4">
    <ul class="pagination justify-content-end">
      <li class="page-item">
        <a class="page-link" href="#" aria-label="Previous">
          <span aria-hidden="true">&laquo;</span>
        </a>
      </li>
      <li class="page-item"><a class="page-link" href="src/home.vue">1</a></li>
      <li class="page-item"><a class="page-link" href="src/profil.vue">2</a></li>
      <li class="page-item"><a class="page-link" href="src/pekerjaan.vue">3</a></li>
      <li class="page-item"><a class="page-link" href="src/about.vue">4</a></li>
      <li class="page-item">
        <a class="page-link" href="#" aria-label="Next">
          <span aria-hidden="true">&raquo;</span>
        </a>
      </li>
    </ul>
  </nav>
  </body>
  <!-- footer -->
  <footer class="bg-success bg-opacity-70 fw-bold text-center pt-1 shadow">
    <p style="color: white">
      Created with <i class="bi bi-heart-fill text-danger"></i> by <a href="https://www.instagram.com/dilll.412/" class="text-white">AIDIL ZIKRI</a>
    </p>
    <p class="text-white ">atau bisa juga ikutin kami di :</p>
    <span class="badge bg-white"><a href="https://web.facebook.com/aidil.zikri.3998/">Facebook <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
      <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
    </svg></a></span>
    <span class="badge bg-white"><a href=" https://twitter.com/aizi412?t=uZspMyu7KuFy9aEs7P4Z3g&s=08">Twitter <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
      <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
    </svg></a></span>
  </footer>
  <!-- penutup footer -->
