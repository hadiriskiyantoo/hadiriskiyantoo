<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.min.css" />

    <script src="js/bootstrap.min.js"></script>
    <!-- boostrap icons -->
    <link rel="stylesheet" href="css/bootstrap.min.css" />

    <script src="js/bootstrap.min.js"></script>
    <!-- mycss -->
    <link rel="stylesheet" href="style.css" />
    <title>My Portfolio</title>
    <style>
      h1 {
        text-align: center;
        color: black;
      }
    </style>
  </head>
  <body id="home">
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-secondary shadow-lg fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">Husein F.</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#projects">Project</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- awal jumbotron -->
    <section class="jumbotron text-center">
      <img src="img/husein.jpeg" alt="Husein Fadhlullah" width="200" class="rounded-circle img-thumbnail" />
      <h1 class="display-4">Husein Fadhlullah</h1>
      <p class="lead">Pelajar | RPL</p>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#f3f4f5"
          fill-opacity="1"
          d="M0,192L26.7,165.3C53.3,139,107,85,160,53.3C213.3,21,267,11,320,26.7C373.3,43,427,85,480,117.3C533.3,149,587,171,640,160C693.3,149,747,107,800,74.7C853.3,43,907,21,960,16C1013.3,11,1067,21,1120,58.7C1173.3,96,1227,160,1280,154.7C1333.3,149,1387,75,1413,37.3L1440,0L1440,320L1413.3,320C1386.7,320,1333,320,1280,320C1226.7,320,1173,320,1120,320C1066.7,320,1013,320,960,320C906.7,320,853,320,800,320C746.7,320,693,320,640,320C586.7,320,533,320,480,320C426.7,320,373,320,320,320C266.7,320,213,320,160,320C106.7,320,53,320,27,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- akhir -->
    <!-- awal about -->
    <section id="about">
      <div class="container">
        <div class="row text-center mb">
          <div class="col">
            <h2>About me</h2>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4">
            <p>Nama Saya Adalah Husein Fadhlullah ,Murid Dari SMKN 5 Kelas XI RPL3</p>
          </div>
          <div class="col-md-4">
            <p>Saya Diberi Tugas Untuk Membuat website menggunaan Bootstrap</p>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill=" darkgray"
          fill-opacity="1"
          d="M0,160L20,154.7C40,149,80,139,120,149.3C160,160,200,192,240,208C280,224,320,224,360,192C400,160,440,96,480,74.7C520,53,560,75,600,96C640,117,680,139,720,128C760,117,800,75,840,90.7C880,107,920,181,960,213.3C1000,245,1040,235,1080,245.3C1120,256,1160,288,1200,256C1240,224,1280,128,1320,90.7C1360,53,1400,75,1420,85.3L1440,96L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- akhir about -->
    <!-- project -->
    <section id="projects">
      <div class="container">
        <div class="row text-center">
          <div class="col">
            <h2>My Projects</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="projects/1.jpg" class="card-img-top" alt="Project 1" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="projects/2.jpg" class="card-img-top" alt="Project 1" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="projects/3.jpg" class="card-img-top" alt="Project 1" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="white"
          fill-opacity="1"
          d="M0,256L30,229.3C60,203,120,149,180,133.3C240,117,300,139,360,128C420,117,480,75,540,90.7C600,107,660,181,720,202.7C780,224,840,192,900,170.7C960,149,1020,139,1080,144C1140,149,1200,171,1260,176C1320,181,1380,171,1410,165.3L1440,160L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- akhir project -->
    <!-- contacs -->
    <section id="contact">
      <div class="row text-center mb-3">
        <div class="col">
          <h2>Contact Me</h2>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <div class="alert alert-warning alert-dismissible fade show d-none my-alert" role="alert">
            <strong>Terima Kasih!</strong> Pesan Anda Sudah Terkirim.
            <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
          </div>
          <form name="wpu-contact-form">
            <div class="mb-3">
              <label for="name" class="form-label">Nama Lengkap</label>
              <input type="text" class="form-control" id="name" aria-describedby="name" name="nama" />
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input type="email" class="form-control" id="email" aria-describedby="email" name="email" />
            </div>
            <div class="mb-3">
              <label for="pesan" class="form-label">Pesan</label>
              <textarea class="form-control" id="pesan" rows="3" name="pesan"></textarea>
            </div>
            <button type="submit" class="btn-kirim btn-dark">Kirim</button>
            <button class="btn btn-dark btn-loading d-none" type="button" disabled>
              <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
              Loading...
            </button>
          </form>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="darkgray"
          fill-opacity="1"
          d="M0,192L48,176C96,160,192,128,288,138.7C384,149,480,203,576,224C672,245,768,235,864,213.3C960,192,1056,160,1152,170.7C1248,181,1344,235,1392,261.3L1440,288L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- akhir contacts -->

    <!-- footer -->
    <footer class="bg-dark text-white text-center pb-3">
      <p>Created With <i class="bi bi-heart-fill text-danger"></i> by <a href="https://www.instagram.com/husen_f2/?hl=en" class="text-white fw-bold">Husein Fadhlullah</a></p>
    </footer>
    <!-- akhirfooter -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <script>
      const scriptURL = "https://script.google.com/macros/s/AKfycbzHBsoiK_-Eea1cVcUqyQ2zwgoxjDsIxujF33NOBD_cT7zGB3U-RDyMvK0_8fTYmCW1/exec";
      const form = document.forms["wpu-contact-form"];
      const btnKirim = document.querySelector(".btn-kirim");
      const btnLoading = document.querySelector(".btn-loading");
      const myAlert = document.querySelector(".my-alert");

      form.addEventListener("submit", (e) => {
        e.preventDefault();
        // ketika tombol submit diklik
        // tampilkan tombol loading,hilangkan tombol kirim
        btnLoading.classList.toggle("d-none");
        btnKirim.classList.toggle("d-none");

        fetch(scriptURL, { method: "POST", body: new FormData(form) })
          .then((response) => {
            // tampilkan tombol kirim,hilangkan tombol loading

            btnLoading.classList.toggle("d-none");
            btnKirim.classList.toggle("d-none");
            // tampilkan alert
            myAlert.classList.toggle("d-none");
            // reset form
            form.reset();

            console.log("Success!", response);
          })
          .catch((error) => console.error("Error!", error.message));
      });
    </script>
  </body>
</html>
