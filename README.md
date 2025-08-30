<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JD SERVICE</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background: #004aad;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    header p {
      margin: 5px 0 0;
      font-style: italic;
    }

    nav {
      background: #003580;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 50px 20px;
      text-align: center;
    }

    section h2 {
      color: #004aad;
      margin-bottom: 20px;
    }

    footer {
      background: #003580;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 30px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .service-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

  <header>
    <h1>JD SERVICE</h1>
    <p>PLUS SUR</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#apropos">À propos</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="accueil">
    <h2>Bienvenue chez JD SERVICE</h2>
    <p>Nous mettons notre expertise à votre service pour répondre à vos besoins avec professionnalisme.</p>
  </section>

  <section id="apropos">
    <h2>À propos</h2>
    <p>JD SERVICE est une entreprise spécialisée dans la prestation de services techniques et technologiques, avec un engagement fort pour la qualité et la satisfaction client.</p>
  </section>

  <section id="services">
    <h2>Nos Services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Installation & Maintenance</h3>
        <p>Des solutions fiables pour vos équipements et systèmes.</p>
      </div>
      <div class="service-card">
        <h3>Réparation</h3>
        <p>Diagnostic et réparation rapide de vos matériels.</p>
      </div>
      <div class="service-card">
        <h3>Conseils Techniques</h3>
        <p>Un accompagnement personnalisé pour vos projets.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📞 Téléphone : <strong>0164438913</strong></p>
    <p>Nous sommes disponibles pour répondre à toutes vos questions.</p>
  </section>

  <footer>
    <p>&copy; 2025 JD SERVICE - Tous droits réservés</p>
  </footer>

</body>
</html>
