<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Agha hairdresser — Services & Contact</title>
  <meta name="description" content="Agha hairdresser — 13 years experience. Specialising in hair up, colour, balayage, haircuts, extensions and treatments. Call to book." />
  <style>
    :root{
      --accent:#d44;           /* primary accent color */
      --accent-2:#333;        /* headings */
      --muted:#666;
      --card:#fff;
      --bg:#f7f7f8;
      --radius:12px;
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:var(--bg);
      color:var(--accent-2);
      line-height:1.45;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:24px;
    }
    .container{
      max-width:980px;
      margin:0 auto;
      display:grid;
      grid-template-columns: 1fr 320px;
      gap:28px;
      align-items:start;
    }

    header{
      grid-column: 1 / -1;
      display:flex;
      gap:18px;
      align-items:center;
      background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(255,255,255,0.95));
      padding:18px;
      border-radius:var(--radius);
      box-shadow:0 6px 20px rgba(20,20,30,0.04);
    }
    .logo{
      width:84px;
      height:84px;
      flex:0 0 84px;
      display:flex;
      align-items:center;
      justify-content:center;
      background:#fff;
      border-radius:10px;
      overflow:hidden;
    }
    .logo img{width:100%;height:100%;object-fit:contain}
    .brand h1{
      margin:0;
      font-size:20px;
      letter-spacing:-0.2px;
      color:var(--accent-2);
    }
    .brand p{margin:6px 0 0;color:var(--muted);font-size:14px}

    /* Main content */
    main{
      background:var(--card);
      padding:20px;
      border-radius:var(--radius);
      box-shadow:0 6px 18px rgba(20,20,30,0.04);
    }
    .lead{
      display:flex;
      gap:14px;
      align-items:center;
      margin-bottom:16px;
    }
    .experience{
      font-weight:700;
      color:var(--accent-2);
    }
    h2{
      margin:6px 0 12px;
      font-size:18px;
      color:var(--accent-2);
    }
    p.lead-text{margin:0 0 14px;color:var(--muted)}
    .services-grid{
      display:grid;
      grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
      gap:12px;
    }

    .card{
      background: #fff;
      padding:12px;
      border-radius:10px;
      border:1px solid rgba(0,0,0,0.03);
    }
    .service-row{
      display:flex;
      justify-content:space-between;
      padding:8px 0;
      border-bottom:1px dashed rgba(0,0,0,0.04);
      font-size:15px;
    }
    .service-row:last-child{border-bottom:0}
    .section-note{font-size:13px;color:var(--muted);margin-top:8px}

    /* Sidebar */
    aside{
      background:var(--card);
      padding:18px;
      border-radius:var(--radius);
      box-shadow:0 6px 18px rgba(20,20,30,0.04);
      position:sticky;
      top:24px;
      height:max-content;
    }
    .contact-block{display:flex;flex-direction:column;gap:10px}
    .phone-btn{
      display:inline-block;
      background:var(--accent);
      color:#fff;
      padding:12px 14px;
      border-radius:10px;
      text-decoration:none;
      font-weight:700;
      text-align:center;
    }
    .socials{display:flex;gap:8px;flex-wrap:wrap}
    .socials a{
      text-decoration:none;
      border:1px solid rgba(0,0,0,0.06);
      padding:8px 10px;
      border-radius:8px;
      font-weight:600;
      color:var(--accent-2);
      font-size:14px;
    }
    address{font-style:normal;color:var(--muted);font-size:14px}
    footer{grid-column:1 / -1;margin-top:18px;text-align:center;color:var(--muted);font-size:13px}

    /* responsive */
    @media (max-width:880px){
      .container{grid-template-columns:1fr; padding:0 6px}
      aside{position:static}
      header{flex-direction:row;gap:12px}
    }
  </style>
</head>
<body>
  <div class="container">

    <header>
      <div class="logo" aria-hidden="false">
        <!-- Replace 'logo.png' with your actual logo filename (JPEG/PNG/SVG) -->
        <img src="logo.png" alt="Agha hairdresser logo" />
      </div>
      <div class="brand">
        <h1>Agha hairdresser</h1>
        <p class="lead-text">13 years of experience — Specialising in hair up, colour, balayage, haircuts, extensions & treatments</p>
      </div>
    </header>

    <main>
      <section aria-labelledby="services-heading">
        <h2 id="services-heading">Services & Prices</h2>

        <div class="services-grid">

          <div class="card" aria-label="Styling and cuts">
            <strong>Styling & Cuts</strong>
            <div class="service-row"><span>Blow dry</span><span>£40</span></div>
            <div class="service-row"><span>Hair cut</span><span>£50</span></div>
            <div class="service-row"><span>Haircut + Blowdry</span><span>£85</span></div>
          </div>

          <div class="card" aria-label="Colour services">
            <strong>Colour</strong>
            <div class="service-row"><span>Toner</span><span>£60</span></div>
            <div class="service-row"><span>Glossing</span><span>£60</span></div>
            <div class="service-row"><span>Roots colour</span><span>£75</span></div>
            <div class="service-row"><span>Full head colour</span><span>£130</span></div>
            <div class="service-row"><span>Half head highlights</span><span>£175</span></div>
            <div class="service-row"><span>Full head highlights</span><span>£275</span></div>
            <div class="service-row"><span>Half head balayage</span><span>£185</span></div>
            <div class="service-row"><span>Full head balayage</span><span>£289</span></div>
          </div>

          <div class="card" aria-label="Hair treatments">
            <strong>Hair treatments</strong>
            <div class="service-row"><span>Keratin</span><span>£210</span></div>
            <div class="service-row"><span>Protein</span><span>£210</span></div>
            <div class="service-row"><span>Botox</span><span>£210</span></div>
            <div class="service-row"><span>Hair mask</span><span>£35</span></div>
          </div>

          <div class="card" aria-label="Extensions">
            <strong>Extensions</strong>
            <div class="section-note">(Hair extensions retap)</div>
            <div class="service-row"><span>Tap-in</span><span>£239</span></div>
            <div class="service-row"><span>Extensions sews</span><span>£215</span></div>
            <div class="service-row"><span>Micro-rings</span><span>£215</span></div>
            <div class="service-row"><span>Pre-bonded</span><span>£215</span></div>
          </div>

        </div>
      </section>

      <section style="margin-top:18px" aria-labelledby="notes-heading">
        <h2 id="notes-heading">About</h2>
        <p class="section-note">13 years experience in hairdressing with a strong focus on hair ups, colour work, balayage, precision haircuts, hair extensions and professional hair treatments. For bespoke pricing (long/thick hair, complex balayage, full extensions sets) please contact for a consultation.</p>
      </section>
    </main>

    <aside>
      <div class="contact-block" role="region" aria-label="Contact information">
        <div>
          <strong style="display:block">Address</strong>
          <address>60 Baker Street<br>W1U 7DE</address>
        </div>

        <div>
          <strong style="display:block;margin-top:8px">Phone</strong>
          <a class="phone-btn" href="tel:07493670608" aria-label="Call Agha hairdresser">Call to book — 07493 670608</a>
        </div>

        <div>
          <strong style="display:block;margin-top:12px">Social</strong>
          <div class="socials" role="list" aria-label="Social links">
            <a role="listitem" href="https://www.instagram.com/agha.hairdresser" target="_blank" rel="noopener noreferrer" aria-label="Instagram — agha.hairdresser">Instagram</a>
            <a role="listitem" href="https://www.tiktok.com/@agha.hairdresser?_t=ZN-90pOuH2hy22&_r=1" target="_blank" rel="noopener noreferrer" aria-label="TikTok — agha.hairdresser">TikTok</a>
          </div>
        </div>

        <div style="margin-top:12px">
          <strong style="display:block">Opening / Notes</strong>
          <p class="section-note">Appointments available — please call or message via Instagram/TikTok to book. For extension consultations bring inspiration photos.</p>
        </div>
      </div>
    </aside>

    <footer>
      © Agha hairdresser — Portfolio / Work showcase
    </footer>

  </div>
</body>
</html>