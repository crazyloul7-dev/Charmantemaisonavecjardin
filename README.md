<!DOCTYPE html><html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maison de vacances</title><link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet"><style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  color: #222;
  background: #fff;
}

/* HERO */
.hero {
  height: 100vh;
  background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://via.placeholder.com/1600x900') center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  text-align: center;
}

.hero h1 {
  font-size: 60px;
  margin: 0;
}

.hero p {
  font-size: 22px;
  margin-top: 10px;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 14px 30px;
  background: white;
  color: black;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 600;
  transition: 0.3s;
}

.btn:hover {
  background: black;
  color: white;
}

/* SECTIONS */
section {
  padding: 80px 20px;
  max-width: 1200px;
  margin: auto;
}

h2 {
  text-align: center;
  font-size: 32px;
  margin-bottom: 40px;
}

/* GRID PHOTOS */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.grid img {
  width: 100%;
  border-radius: 20px;
  transition: transform 0.3s ease;
}

.grid img:hover {
  transform: scale(1.05);
}

/* FEATURES */
.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.feature {
  background: #f7f7f7;
  padding: 25px;
  border-radius: 15px;
  text-align: center;
  font-weight: 500;
}

/* SPLIT SECTION */
.split {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  align-items: center;
}

.split img {
  width: 100%;
  border-radius: 20px;
}

/* CONTACT */
.contact-box {
  text-align: center;
  background: #111;
  color: white;
  padding: 50px;
  border-radius: 20px;
}

/* FOOTER */
footer {
  background: #000;
  color: white;
  text-align: center;
  padding: 30px;
  margin-top: 40px;
}

/* MOBILE */
@media(max-width: 800px) {
  .hero h1 { font-size: 40px; }
  .split { grid-template-columns: 1fr; }
}

</style></head>
<body><!-- HERO --><div class="hero">
  <div>
    <h1>[Nom de la maison]</h1>
    <p>Une expérience unique à [ville]</p>
    <a href="#contact" class="btn">Réserver maintenant</a>
  </div>
</div><!-- DESCRIPTION --><section class="split">
  <img src="https://via.placeholder.com/600x400">
  <div>
    <h2>Un lieu d'exception</h2>
    <p>
      Profitez d’un séjour inoubliable dans une maison pensée pour votre confort.
      Idéale pour se détendre, se retrouver et profiter d’un cadre unique.
    </p>
  </div>
</section><!-- FEATURES --><section>
  <h2>Équipements</h2>
  <div class="features">
    <div class="feature">Wi-Fi haut débit</div>
    <div class="feature">Cuisine équipée</div>
    <div class="feature">Piscine privée</div>
    <div class="feature">Parking gratuit</div>
  </div>
</section><!-- PHOTOS --><section>
  <h2>Galerie</h2>
  <div class="grid">
    <img src="https://drive.google.com/uc?export=view&id=14iHL280wHNVN9czuZGHjKOYfEQ12pd_I">
    <img src="https://drive.google.com/uc?export=view&id=1W4l14Y-QMHKxLPagM7Bn7pCU0F4MdoQ4">
    <img src="https://drive.google.com/uc?export=view&id=1aAaYiuYspUipvRYH4sxfpgHTZXnAMdIm">
    <img src="https://drive.google.com/uc?export=view&id=1ZA68GePGu_FA1NsXKR8BI-7l6PGWYDM2">
  </div>
</section><!-- TARIFS --><section>
  <h2>Tarifs</h2>
  <p style="text-align:center; font-size:20px;">À partir de XX€/nuit</p>
</section><!-- CONTACT --><section id="contact">
  <div class="contact-box">
    <h2>Réserver votre séjour</h2>
    <p>Email : flavien.v@laposte.net</p>
    <p>Téléphone : +33638701428</p>
  </div>
</section><footer>
  <p>© 2026 - Maison de vacances</p>
</footer></body>
</html>
