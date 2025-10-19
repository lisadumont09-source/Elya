<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Éditions Notambule — Maquette</title>
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f7f3ef;
      --accent:#b88a5a;
      --muted:#6b6460;
      --paper:#fffaf5;
      --serif:'Playfair Display', 'Merriweather', serif;
      --sans: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      --maxw:900px;
    }
    *{box-sizing:border-box}
    body{font-family:var(--serif);background:linear-gradient(180deg,var(--bg),#efe9e0);color:#222;margin:0;padding:40px 20px;display:flex;justify-content:center}
    .site{width:100%;max-width:var(--maxw);background:var(--paper);box-shadow:0 8px 30px rgba(20,20,20,0.08);border-radius:8px;overflow:hidden}
    header{padding:28px 34px;border-bottom:1px solid rgba(0,0,0,0.06);display:flex;align-items:center;gap:18px}
    .logo{width:68px;height:68px;border-radius:6px;background:linear-gradient(135deg,var(--accent),#caa680);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-family:var(--sans)}
    .brand h1{font-family:var(--serif);font-size:20px;margin:0}
    .brand p{margin:2px 0 0 0;color:var(--muted);font-size:13px}

    .hero{display:grid;grid-template-columns:1fr 440px;gap:28px;padding:34px}
    .left{padding-right:8px}
    .book-title{font-size:44px;line-height:1.02;margin:0 0 10px 0}
    .book-author{font-size:18px;color:var(--muted);margin:0 0 18px 0}
    .meta{display:flex;gap:12px;align-items:center;color:var(--muted);font-size:13px}
    .description{margin-top:18px;color:#3a352f;line-height:1.6;font-size:15px}

    .cover{background:#f1ebe3;border:1px solid rgba(0,0,0,0.04);padding:18px;display:flex;flex-direction:column;align-items:center;justify-content:flex-start;border-radius:6px;margin-top:18px}
    .cover img{width:100%;height:auto;border-radius:4px;box-shadow:0 6px 20px rgba(0,0,0,0.06)}
    .cover .caption{margin-top:12px;font-size:13px;color:var(--muted)}

    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;padding:28px;border-top:1px solid rgba(0,0,0,0.04)}
    .card{background:white;padding:16px;border-radius:6px;box-shadow:0 6px 18px rgba(10,10,10,0.04)}
    .card h3{margin:0 0 10px 0;font-size:15px}
    .card p{margin:0;color:var(--muted);font-size:13px}

    footer{padding:18px 34px;border-top:1px solid rgba(0,0,0,0.04);display:flex;justify-content:space-between;align-items:center}
    .editor{font-size:13px;color:var(--muted)}

    @media (max-width:880px){
      .hero{grid-template-columns:1fr;}
      .cover{order:-1;margin-bottom:18px}
      .grid{grid-template-columns:repeat(1,1fr)}
    }

    .badge{position:fixed;right:18px;bottom:18px;background:rgba(255,255,255,0.95);border:1px solid rgba(0,0,0,0.06);padding:10px 12px;border-radius:6px;font-size:13px;color:#4b443f;box-shadow:0 6px 20px rgba(10,10,10,0.06)}
  </style>
</head>
<body>
  <div class="site" role="main">
    <header>
      <div class="logo">EN</div>
      <div class="brand">
        <h1>Éditions Notambule</h1>
        <p>Maquette — collection théâtre & littérature</p>
      </div>
    </header>

    <section class="hero">
      <div class="left">
        <h2 class="book-title">Homicide</h2>
        <p class="book-author">par Elya AMIC, Nelly BEL & Tess DECHAUX</p>

        <!-- Illustration du journal en dessous du titre -->
        <div class="cover">
          <img src="https://via.placeholder.com/380x540.png?text=Illustration+Journal" alt="Illustration du journal pour Homicide">
          <div class="caption">Journal illustratif : Tentative de braquage déjouée à Décathlon…</div>
        </div>

        <div class="meta">
          <div>Format : Broché</div>
          <div>Pages : 128</div>
          <div>ISBN : 978-0-000000-0</div>
        </div>

        <p class="description">Le journal baigne dans une flaque d'eau sale, capturant une ambiance réaliste et dramatique.</p>

        <div style="margin-top:18px;display:flex;gap:12px">
          <a href="#acheter" style="text-decoration:none;background:var(--accent);color:white;padding:10px 14px;border-radius:6px;font-weight:600">Acheter / Commander</a>
          <a href="#extrait" style="text-decoration:none;border:1px solid rgba(0,0,0,0.08);padding:10px 14px;border-radius:6px;color:var(--muted)">Lire un extrait</a>
        </div>
      </div>
    </section>

    <section class="grid">
      <div class="card">
        <h3>À propos des auteures</h3>
        <p>Elya AMIC, Nelly BEL et Tess DECHAUX sont des autrices et illustratrices explorant la littérature contemporaine avec un style poétique et réaliste.</p>
      </div>
      <div class="card">
        <h3>Extrait</h3>
        <p>« Les pages trempées reflétaient la lumière du lampadaire, chaque mot semblait flotter dans la flaque sale… » (Extrait disponible sur demande.)</p>
      </div>
      <div class="card">
        <h3>Crédits</h3>
        <p>Illustrations : Elya AMIC, Nelly BEL, Tess DECHAUX. Mise en page : Maquette interne. Éditeur fictif : Éditions Notambule.</p>
      </div>
    </section>

    <footer>
      <div class="editor">Éditions Notambule</div>
      <div style="color:var(--muted);font-size:13px">© Maquette — usage démo</div>
    </footer>
  </div>

  <div class="badge">Maquette / Site de démonstration — ne pas présenter comme site officiel</div>

</body>
</html>
