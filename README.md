<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Choisissez votre Plan</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-image: url('image.png');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      color: #fff;
      text-align: center;
    }

    h1 span {
      color: yellow;
    }

    .container {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 60px 20px;
      flex-wrap: wrap;
    }

    .card {
      background-color: rgba(0, 0, 0, 0.7);
      border: 2px solid yellow;
      border-radius: 10px;
      width: 300px;
      padding: 30px 20px;
      box-shadow: 0 0 15px rgba(255, 255, 0, 0.2);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .price {
      font-size: 2em;
      color: yellow;
      margin: 10px 0;
    }

    ul {
      text-align: left;
      padding-left: 0;
      list-style: none;
      margin-top: 20px;
    }

    ul li::before {
      content: "✔️ ";
      color: yellow;
    }

    button {
      margin-top: 25px;
      padding: 12px 25px;
      font-size: 1em;
      background-color: yellow;
      border: none;
      color: black;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #ffd700;
    }

    .tag {
      color: yellow;
      font-weight: bold;
      margin-bottom: 10px;
      font-size: 1.1em;
    }

    .payment-section {
      margin-top: 80px;
      padding: 20px;
    }

    .pay-methods {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 50px;
    }

    .method {
      background: rgba(0, 0, 0, 0.7);
      border: 2px solid yellow;
      border-radius: 10px;
      padding: 20px;
      width: 260px;
      text-align: center;
    }

    .method img {
      width: 50px;
      margin-bottom: 10px;
    }

    .address {
      color: yellow;
      word-wrap: break-word;
      font-size: 0.9em;
      background: #222;
      padding: 10px;
      border-radius: 5px;
    }

    .discord-link {
      margin-top: 60px;
    }

    .discord-link a {
      color: black;
      background-color: yellow;
      padding: 15px 30px;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      transition: background 0.3s;
    }

    .discord-link a:hover {
      background-color: #ffd700;
    }
  </style>
</head>
<body>

  <h1><span>Choisissez</span> Votre Plan</h1>
  <p>Sélectionnez l’abonnement qui vous convient le mieux</p>

  <div class="container">

    <!-- Snusbase -->
    <div class="card">
      <div class="tag">Snusbase</div>
      <div class="price">4,99€ / mois</div>
      <ul>
        <li>Accès à la base de données Snusbase</li>
        <li>Recherche par email, username ou domaine</li>
        <li>Export en CSV</li>
        <li>Support Discord</li>
      </ul>
      <button>S’ABONNER</button>
    </div>

    <!-- Intelx -->
    <div class="card">
      <div class="tag">IntelX</div>
      <div class="price">40€ / mois</div>
      <ul>
        <li>Moteur OSINT avancé</li>
        <li>Recherche dans le darkweb, leaks, documents</li>
        <li>Export de données JSON/CSV</li>
        <li>Accès prioritaire aux requêtes</li>
      </ul>
      <button>S’ABONNER</button>
    </div>

    <!-- C2 DDoS -->
    <div class="card">
      <div class="tag">C2 (DDoS)</div>
      <div class="price">2 Boost Discord</div>
      <ul>
        <li>Outil de DDoS personnalisé</li>
        <li>Accès C2 avec interface Web</li>
        <li>Logs des attaques en temps réel</li>
        <li>Support technique privé</li>
      </ul>
      <button>S’ABONNER</button>
    </div>

  </div>

  <div class="payment-section">
    <h2><span>Paiement</span> sécurisé</h2>
    <div class="pay-methods">

      <!-- Litecoin -->
      <div class="method">
        <img src="image.png" alt="Litecoin">
        <p>Payer en Litecoin :</p>
        <div class="address">LPVpADBDHB8BFYtVJfar3YHHtsMSw4Qpsh</div>
        <p><small>Copiez l’adresse dans votre wallet</small></p>
      </div>

      <!-- PayPal -->
      <div class="method">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" alt="PayPal" style="width:60px">
        <p>Payer avec PayPal :</p>
        <a href="https://www.paypal.me/shippeur2" target="_blank">
          <button>Payer via PayPal</button>
        </a>
      </div>

    </div>
  </div>

  <!-- Discord -->
  <div class="discord-link">
    <h2>🔗 Rejoins-nous sur Discord</h2>
    <a href="https://discord.gg/LookBase" target="_blank">Accéder au serveur</a>
  </div>

</body>
</html>
