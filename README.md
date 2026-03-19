<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maison de vacances</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; }
    header { background: url('https://via.placeholder.com/1200x500') center/cover; color: white; padding: 100px 20px; text-align: center; }
    nav { background: #333; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; }
    .grid img { width: 100%; border-radius: 10px; }
    .btn { background: #007BFF; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; }
    footer { background: #222; color: white; text-align: center; padding: 20px; }
  </style>
</head>
<body>

<header>
  <h1>Bienvenue à [Nom de la maison]</h1>
  <p>Votre séjour idéal à [Saint jean fe monts]</p>
  <a href="#contact" class="btn">Réserver</a>
</header>

<nav>
  <a href="#maison">La maison</a>
  <a href="#photos">Photos</a>
  <a href="#tarifs">Tarifs</a>
  <a href="#contact">Contact</a>
</nav>

<section id="maison">
  <h2>La maison</h2>
  <p>Maison confortable pour 4 à 6 personnes avec tout le nécessaire : cuisine équipée, Wi-Fi, jardin, etc.</p>
</section>

<section id="photos">
  <h2>Photos</h2>
  <div class="grid">
    <img src="https://drive.google.com/file/d/1ZA68GePGu_FA1NsXKR8BI-7l6PGWYDM2/view?usp=drivesdk">
    <img src="https://drive.google.com/file/d/1_Krn71pA4f-tlaR9nipgYaDhaQVeljM5?usp=drivesdk">
    <img src="https://drive.google.com/file/d/14iHL280wHNVN9czuZGHjKOYfEQ12pd_I/view?usp=drivesdk">
  </div>
</section>

<section id="tarifs">
  <h2>Tarifs</h2>
  <p>À partir de 89€/nuit</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email : flavien.v@laposte.net</p>
  <p>Téléphone : +33638701428</p>
</section>

<footer>
  <p>© 2026 - Maison de vacances classée 4 étoiles</p>
</footer>

</body>
</html>
