<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chiosco al Ponte — Trattoria</title>
  <style>
    :root{--accent:#b8332b;--muted:#666;--card:#fff;--bg:#f6f6f6}
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; background:var(--bg); color:#222}
    header{background:linear-gradient(90deg,rgba(0,0,0,0.25),rgba(0,0,0,0.05)),url('') center/cover no-repeat; padding:36px 16px}
    .wrap{max-width:1100px;margin:0 auto}
    .brand{display:flex;align-items:center;gap:16px}
    .brand h1{margin:0;font-size:28px;color:var(--accent)}
    nav{margin-top:12px}
    nav a{margin-right:14px;color:var(--muted);text-decoration:none}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:24px;align-items:start}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.06)}
    .section{margin:20px 0}
    .grid{display:flex;gap:12px;flex-wrap:wrap}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:#fff;text-decoration:none}
    footer{padding:24px 16px;color:var(--muted);font-size:14px}
    ul.meta{list-style:none;padding:0;margin:0}
    ul.meta li{margin:8px 0}
    .menu-item{display:flex;justify-content:space-between;padding:8px 0;border-bottom:1px dashed #eee}
    img.responsive{width:100%;height:auto;border-radius:8px}
    @media (max-width:900px){.hero{grid-template-columns:1fr;}.brand h1{font-size:22px}}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <div class="brand">
        <div style="width:64px;height:64px;border-radius:8px;background:var(--card);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent)">CP</div>
        <div>
          <h1>Chiosco al Ponte</h1>
          <div style="color:var(--muted)">Trattoria — Località Ponte di Togliano, Torreano (UD)</div>
        </div>
      </div>
      <nav>
        <a href="#menu">Menù</a>
        <a href="#info">Info</a>
        <a href="#gallery">Galleria</a>
        <a href="#contatti">Contatti</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <section class="hero section">
      <div class="card">
        <h2>Benvenuti al Chiosco al Ponte</h2>
        <p style="color:var(--muted)">Cucina tradizionale friulana in un ambiente informale. Piatti tipici, frico, carne alla griglia e un'ottima selezione di vini locali.</p>

        <div style="margin-top:12px" class="grid">
          <a class="btn" href="tel:+390432715327">Prenota ora — +39 0432 715327</a>
          <a class="btn" style="background:#444" href="https://www.google.com/maps/place/Chiosco+al+Ponte/@46.1108994,13.4012297,17z">Apri su Google Maps</a>
        </div>

        <div style="margin-top:18px">
          <h3>Orari</h3>
          <ul class="meta">
            <li>Pranzo: 12:00 — 14:30</li>
            <li>Cena: 19:00 — 22:30</li>
            <li>Chiuso il Lunedì (verificare sul posto)</li>
          </ul>
        </div>

        <div style="margin-top:18px">
          <h3>Consigli dello chef</h3>
          <ul>
            <li>Frico "alla Giulietta"</li>
            <li>Tagliata di manzo con contorni stagionali</li>
            <li>Polenta e goulash</li>
          </ul>
        </div>
      </div>

      <aside class="card">
        <h3>Informazioni rapide</h3>
        <ul class="meta">
          <li><strong>Indirizzo:</strong> Località Ponte di Togliano, Torreano (UD)</li>
          <li><strong>Telefono:</strong> +39 0432 715327</li>
          <li><strong>Servizi:</strong> Prenotazioni, menù locale, tavoli all'aperto</li>
          <li><strong>Accessibilità:</strong> ingresso piano (controllare disponibilità tavoli esterni)</li>
        </ul>

        <div style="margin-top:12px">
          <a class="btn" href="#contatti">Contattaci</a>
        </div>
      </aside>
    </section>

    <section id="menu" class="section">
      <div class="card">
        <h2>Menù (estratto)</h2>
        <div>
          <div class="menu-item"><div>Antipasto misto della casa</div><div>€ 12</div></div>
          <div class="menu-item"><div>Frico tradizionale</div><div>€ 10</div></div>
          <div class="menu-item"><div>Tagliata di manzo (200g)</div><div>€ 18</div></div>
          <div class="menu-item"><div>Polenta con goulash</div><div>€ 13</div></div>
          <div class="menu-item"><div>Dolci fatti in casa</div><div>€ 6</div></div>
        </div>
        <p style="color:var(--muted);margin-top:10px">Per il menù completo e le offerte stagionali contattare il ristorante o visitare la pagina Google/TripAdvisor.</p>
      </div>
    </section>

    <section id="gallery" class="section">
      <div class="card">
        <h2>Galleria</h2>
        <p style="color:var(--muted)">Scorci del locale e dei piatti (foto a titolo informativo).</p>
        <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:12px">
          <img class="responsive" src="https://www.sluurpy.it/img/ristorante/131123/1_400.jpg" alt="Interno Chiosco al Ponte">
          <img class="responsive" src="https://media-cdn.tripadvisor.com/media/photo-s/0a/12/34/56/example.jpg" alt="Piatti tipici" onerror="this.style.display='none'">
          <img class="responsive" src="https://www.restaurantguru.it/images/restaurant/12345/cover.jpg" alt="Esterno">
        </div>
      </div>
    </section>

    <section id="info" class="section">
      <div class="card">
        <h2>Informazioni pratiche & Policy</h2>
        <p style="color:var(--muted)">Per gruppi numerosi/chiedere menù personalizzati o celiaci: chiamare il numero indicato. I prezzi possono variare per eventi e festività.</p>
      </div>
    </section>

    <section id="contatti" class="section">
      <div class="card">
        <h2>Contatti</h2>
        <p>Telefono: <a href="tel:+390432715327">+39 0432 715327</a></p>
        <p>Indirizzo: Località Ponte di Togliano, Torreano (UD)</p>

        <div style="margin-top:12px">
          <h3>Posizione</h3>
          <div style="height:300px;border-radius:8px;overflow:hidden">
            <iframe width="100%" height="100%" frameborder="0" style="border:0" src="https://maps.google.com/maps?q=46.1108994,13.40381&z=15&output=embed" allowfullscreen></iframe>
          </div>
        </div>

        <div style="margin-top:12px">
          <h3>Modulo rapido</h3>
          <form onsubmit="event.preventDefault(); alert('Grazie — il messaggio è simulato in questa demo.');">
            <div style="display:flex;gap:8px;flex-direction:column">
              <input placeholder="Nome" required style="padding:10px;border-radius:8px;border:1px solid #e6e6e6">
              <input placeholder="Email" type="email" required style="padding:10px;border-radius:8px;border:1px solid #e6e6e6">
              <textarea placeholder="Messaggio / Richiesta" rows="4" style="padding:10px;border-radius:8px;border:1px solid #e6e6e6"></textarea>
              <button class="btn" type="submit">Invia</button>
            </div>
          </form>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="wrap">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© <strong>Chiosco al Ponte</strong> — Tutti i diritti riservati</div>
        <div style="color:var(--muted)">Link utili: <a href="#menu">Menù</a> • <a href="#contatti">Contatti</a> • <a href="https://www.tripadvisor.it/Restaurant_Review-g2207935-d2197892-Reviews-Trattoria_Chiosco_al_Ponte-Torreano_Province_of_Udine_Friuli_Venezia_Giulia.html">Recensioni</a></div>
      </div>
    </div>
  </footer>
</body>
</html>
