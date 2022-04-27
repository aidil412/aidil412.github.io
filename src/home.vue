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
            <a class="nav-link active" aria-current="page" href="App.vue">App</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page"><b>HOME </b> <i class="bi bi-house-fill text-white"></i></a>
          </li>
            <li class="nav-item">
              <a class="nav-link" href="profil.vue">Profil</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="pekerjaan.vue">Kegiatan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="about.vue">About</a>
            </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- penutup navbar -->

  <h1 style="color: white" class="text-center pd-5 mt-5">
    <span class="badge bg-secondary">Kenapa kuliah itu Penting ?</span>
  </h1>


  <h1 style="color: white" class="text-center">
    ini halaman home
  </h1>

  <div class="clearfix ms-3">
    <img src="../src/assets/kuliah1.jpg" class="col-md-6 float-md-end mb-3 ms-md-3 img-thumbnail" alt="..." width="200"
         height="200">

    <p>
      Makin tinggi pendidikan seseorang maka kesempatan berkarier juga akan semakin luas. Hal ini dikarenakan banyaknya kualifikasi perusahaan yang mengisyaratkan lulusan diploma hingga S1 dalam suatu bidang pekerjaan.
    </p>

    <p>
      Alasan mengapa kuliah penting adalah untuk menemukan relasi baru dan membuka jaringan pertemanan dengan luas. Kalian juga akan belajar dengan orang-orang yang memiliki minat dan bakat yang sama dengan kalian.
      Karena kesamaan latar belakang tersebutlah, kalian dapat bertukar informasi dan berbagi pengalaman untuk mendapatkan banyak kesempatan dan belajar hal-hal baru.
    </p>

    <p>
      Menurut survei yang dilakukan Times Higher Education menjelaskan alasan utama siswa berkuliah karena ingin mempertajam bidang yang sedang dipelajari. Selama berkuliah, dosen akan menerangkan suatu obyek dan membahasnya lebih dalam.
      Dari penjelasan dosen tersebut dapat menemukan minat dan bakat secara lebih mendalam.
    </p>
  </div>
  <section id="saran" class="pd-10 mt-4">
    <div class="container">
      <div class="row text-center">
        <div class="col">
          <h4>Jika ingin memberikan saran dapat dilakukan dibawah ini</h4>
        </div>
      </div>
    </div>
  </section>

  <!-- kontak -->
  <div class="row justify-content-center">
    <div class="col-md-5">
      <form>
        <div class="mb-3">
          <label for="name" class="form-label">Nama</label>
          <input type="text" class="form-control" id="name" aria-describedby="name">
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" aria-describedby="email">
        </div>
        <div class="mb-3">
          <label for="pesan" class="form-label">pesan</label>
          <textarea class="form-control" id="pesan" rows="3"></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Kirim</button>
      </form>
    </div>
  </div>
  <!-- penutup kontak -->

  <!-- project -->
  <section id="project" style="background-color: #008080">
    <div class="container">
      <div class="row text-center pt-4 pb-4">
        <div class="col text-white">
          <h3><b>Postingan Terbaru</b></h3>
        </div>
      </div>
      <div class="row">
        <div class="col-md-4 mb-3">
          <div class="card">
            <img src="assets/kuliah1.jpg" class="card-img-top" alt="KULIAH1">
            <div class="card-body">
              <p class="card-text">Peluang kerja bagi lulusan Teknik Informatika</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-3">
          <div class="card">
            <img src="assets/kuliah2.jpg" class="card-img-top" alt="KULIAH2">
            <div class="card-body">
              <p class="card-text">Mengenal jurusan Teknik Informatika, jurusan yang paling dicari untuk saat ini</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-3">
          <div class="card">
            <img src="assets/kuliah3.jpg" class="card-img-top" alt="KULIAH3">
            <div class="card-body">
              <p class="card-text">Minat baca rendah tapi tutur kata tinggi</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- akhir project -->

  <!-- footer -->
  <footer class="bg-success bg-opacity-70 fw-bold text-center pt-3 shadow">
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

  </body>