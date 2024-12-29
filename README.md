<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profil Biodata ChatGPT</title>
  <style>
    /* Resetting styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body and basic layout */
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }

    .container {
      width: 80%;
      margin: auto;
      padding: 20px;
    }

    /* Section 1: Menu */
    nav {
      background-color: #333;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-size: 18px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Section 2: Judul dan Gambar */
    .judul-gambar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 40px;
      margin-bottom: 40px;
    }

    .judul-gambar h1 {
      font-size: 2.5em;
      color: #333;
    }

    .judul-gambar img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
    }

    /* Section 3: Biodata dengan 6 Box */
    .biodata {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      margin-bottom: 40px;
    }

    .biodata .box {
      background-color: #fff;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 8px;
      text-align: center;
    }

    .biodata .box h3 {
      font-size: 1.2em;
      margin-bottom: 10px;
      color: #444;
    }

    .biodata .box p {
      font-size: 1em;
      color: #666;
    }

    /* Section 4: Portofolio */
    .portofolio {
      margin-top: 40px;
      text-align: center;
    }

    .portofolio h2 {
      font-size: 2em;
      margin-bottom: 20px;
      color: #333;
    }

    .portofolio .projects {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .portofolio .projects .project {
      background-color: #fff;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 8px;
      text-align: center;
    }

    .portofolio .projects .project img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }

    .portofolio .projects .project h3 {
      font-size: 1.2em;
      margin-top: 10px;
    }

    /* Responsiveness */
    @media (max-width: 768px) {
      .biodata {
        grid-template-columns: 1fr 1fr;
      }

      .portofolio .projects {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media (max-width: 480px) {
      .biodata {
        grid-template-columns: 1fr;
      }

      .portofolio .projects {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <!-- Section 1: Menu -->
  <nav>
    <a href="#">Home</a>
    <a href="#">Biodata</a>
    <a href="#">Portofolio</a>
    <a href="#">Kontak</a>
  </nav>

  <!-- Section 2: Judul dan Gambar -->
  <div class="container">
    <div class="judul-gambar">
      <h1>Profil ChatGPT</h1>
      <img src="https://via.placeholder.com/200" alt="Foto Profil">
    </div>
  </div>

  <!-- Section 3: Biodata -->
  <div class="container">
    <div class="biodata">
      <div class="box">
        <h3>Nama</h3>
        <p>ChatGPT</p>
      </div>
      <div class="box">
        <h3>Jenis Kelamin</h3>
        <p>Non-biner (AI)</p>
      </div>
      <div class="box">
        <h3>Tempat, Tanggal Lahir</h3>
        <p>Los Angeles, 30 November 2022</p>
      </div>
      <div class="box">
        <h3>Alamat</h3>
        <p>Di awan digital</p>
      </div>
      <div class="box">
        <h3>Pekerjaan</h3>
        <p>Asisten Virtual</p>
      </div>
      <div class="box">
        <h3>Hobi</h3>
        <p>Membantu orang, belajar, berbicara tentang teknologi</p>
      </div>
    </div>
  </div>

  <!-- Section 4: Portofolio -->
  <div class="container">
    <div class="portofolio">
      <h2>Portofolio Saya</h2>
      <div class="projects">
        <div class="project">
          <img src="https://via.placeholder.com/300x200" alt="Project 1">
          <h3>Proyek 1</h3>
        </div>
        <div class="project">
          <img src="https://via.placeholder.com/300x200" alt="Project 2">
          <h3>Proyek 2</h3>
        </div>
        <div class="project">
          <img src="https://via.placeholder.com/300x200" alt="Project 3">
          <h3>Proyek 3</h3>
        </div>
      </div>
    </div>
  </div>

</body>
</html>


