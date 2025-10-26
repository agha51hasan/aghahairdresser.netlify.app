<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Agha hairdresser — Hair • Colour • Balayage • Extensions</title>
  <meta name="description" content="Agha hairdresser — 13 years experience. Specialising in hair up, colour, balayage, haircuts, extensions and hair treatments. Located at 60 Baker Street, W1U 7DE." />
  <style>
    :root{
      --bg: #fffefc;
      --card: #ffffff;
      --muted: #666666;
      --accent: #b86b2e; /* warm honey/caramel */
      --accent-2: #8c4e22;
      --border: #eee7e2;
      --radius: 12px;
      --max-width: 1100px;
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
      color: #222;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg,#fff 0%,var(--bg)100%);
      padding:28px 18px;
      display:flex;
      justify-content:center;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    .wrap{
      width:100%;
      max-width:var(--max-width);
      display:grid;
      grid-template-columns: 1fr 360px;
      gap:22px;
      align-items:start;
    }

    /* Header / hero */
    header.site-header{
      grid-column: 1 / -1;
      display:flex;
      gap:18px;
      align-items:center;
      margin-bottom:4px;
    }
    .logo{
      width:108px;
      height:108px;
      border-radius:14px;
      background:linear-gradient(135deg, rgba(184,107,46,0.08), rgba(184,107,46,0.02));
      display:flex;
      align-items:center;
      justify-content:center;
      overflow:hidden;
      border:1px solid var(--border);
      box-shadow:0 8px 20px rgba(20,20,20,0.06);
      flex-shrink:0;
    }
    .logo img{ width:100%; height:100%; object-fit:cover; display:block; }

    .brand h1{
      margin:0;
      font-size:22px;
      letter-spacing:0.2px;
    }
    .brand p{ margin:6px 0 0; color:var(--muted); font-size:15px; }

    .tagline{
      margin-top:10px;
      color:var(--accent-2);
      font-weight:600;
      font-size:14px;
    }

    /* Left column card */
    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:16px;
      box-shadow:0 6px 18px rgba(20,20,20,0.04);
      border:1px solid var(--border);
    }

    .chips{ display:flex; gap:8px; flex-wrap:wrap; margin-top:12px; }
    .chip{ background:#fff; border:1px solid #faefe3; padding:6px 10px; border-radius:999px; color:#5a3b2a; font-size:13px; }

    h2.section-title{ margin:0 0 12px 0; font-size:18px; color:#151515; }

    /* services grid */
    .services-grid{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:12px;
    }
    .service-group{ padding:12px; border-radius:8px; background:linear-gradient(180deg,#fff,#fffefc); border:1px solid var(--border); }
    table{ width:100%; border-collapse:collapse; margin-top:8px; font-size:15px; }
    td, th{ padding:8px 6px; border-bottom:1px dashed #f5efe9; vertical-align:middle; }
    td.price{ text-align:right; font-weight:700; color:var(--accent-2); width:110px; }

    /* right column */
    aside.contact{
      position:sticky;
      top:28px;
      height:max-content;
    }
    .contact .addr strong{ display:block; }
    .contact a{ color:var(--accent-2); text-decoration:none; font-weight:700; display:inline-block; margin-top:6px; }
    .socials{ display:flex; gap:8px; margin-top:10px; }
    .socials a{ padding:8px 10px; border-radius:8px; border:1px solid #f0e6df; text-decoration:none; color:#222; font-weight:600; font-size:14px; }

    /* small utilities */
    .note { margin-top:10px; color:var(--muted); font-size:14px; }
    .hero-photo{ width:100%; border-radius:10px; margin-top:12px; box-shadow:0 8px 22px rgba(20,20,20,0.06); display:block; }

    footer{ grid-column:1 / -1; margin-top:14px; text-align:center; color:var(--muted); font-size:14px; }

    /* responsive */
    @media (max-width:980px){
      .wrap{ grid-template-columns: 1fr; }
      aside.contact{ position:relative; top:auto; }
      .logo{ width:86px; height:86px; }
    }
  </style>
</head>
<body>
  <div class="wrap">

    <!-- header -->
    <header class="site-header">
      <!-- Logo image: place your logo file at images/logo.jpg or change the src to match your upload -->
      <div class="logo" aria-hidden="false">
        <img src="images/logo.jpg" alt="Agha hairdresser logo (replace with your file)" onerror="this.style.display='block'; this.parentElement.style.background='#f7f3f0'; this.alt='Logo not found - please upload images/logo.jpg';" />
      </div>

      <div class="brand">
        <h1>Agha hairdresser</h1>
        <p>13 years of experience — Specialising in hair up, colour, balayage, haircuts, extensions & treatments</p>
        <div class="tagline">This site is just to showcase my work</div>
        <div class="chips" aria-hidden="false">
          <span class="chip">Hair Up</span>
          <span class="chip">Colour</span>
          <span class="chip">Balayage</span>
          <span class="chip">Haircut</span>
          <span class="chip">Extensions</span>
          <span class="chip">Treatments</span>
        </div>
      </div>
    </header>

    <!-- left: main content -->
    <main>
      <section class="card">
        <h2 class="section-title">Services & Prices</h2>

        <div class="services-grid">
          <div class="service-group">
            <strong>Styling & Cuts</strong>
            <table aria-label="Styling and cuts">
              <tbody>
                <tr><td>Blow dry</td><td class="price">£40</td></tr>
                <tr><td>Hair cut</td><td class="price">£50</td></tr>
                <tr><td>Haircut & blowdry</td><td class="price">£85</td></tr>
              </tbody>
            </table>
          </div>

          <div class="service-group">
            <strong>Colour Services</strong>
            <table aria-label="Colour services">
              <tbody>
                <tr><td>Toner</td><td class="price">£60</td></tr>
                <tr><td>Glossing</td><td class="price">£60</td></tr>
                <tr><td>Roots colour</td><td class="price">£75</td></tr>
                <tr><td>Full head colour</td><td class="price">£130</td></tr>
                <tr><td>Half head highlights</td><td class="price">£175</td></tr>
                <tr><td>Full head highlights</td><td class="price">£275</td></tr>
                <tr><td>Half head balayage</td><td class="price">£185</td></tr>
                <tr><td>Full head balayage</td><td class="price">£289</td></tr>
              </tbody>
            </table>
          </div>

          <div class="service-group">
            <strong>Hair Treatments</strong>
            <table aria-label="Hair treatments">
              <tbody>
                <tr><td>Keratin</td><td class="price">£210</td></tr>
                <tr><td>Protein</td><td class="price">£210</td></tr>
                <tr><td>Botox</td><td class="price">£210</td></tr>
                <tr><td>Hair mask</td><td class="price">£35</td></tr>
              </tbody>
            </table>
          </div>

          <div class="service-group">
            <strong>Extensions</strong>
            <table aria-label="Extensions">
              <tbody>
                <tr><td>Tap-in (retap)</td><td class="price">£239</td></tr>
                <tr><td>Extensions sews</td><td class="price">£215</td></tr>
                <tr><td>Micro-rings</td><td class="price">£215</td></tr>
                <tr><td>Pre-bonded</td><td class="price">£215</td></tr>
              </tbody>
            </table>
          </div>
        </div>

        <p class="note">This page is a portfolio to show people my work. For appointments please call or message.</p>
      </section>
    </main>

    <!-- right: contact -->
    <aside class="card contact" aria-label="Contact information">
      <h2 class="section-title">Contact</h2>

      <div class="addr">
        <strong>60 Baker Street</strong>
        <div>W1U 7DE</div>
      </div>

      <div style="margin-top:12px">
        <div style="font-weight:700; color:var(--accent-2)">Phone</div>
        <a href="tel:07493670608">07493 670608</a>
      </div>

      <div style="margin-top:12px">
        <div style="font-weight:700; color:var(--accent-2)">Social</div>
        <div class="socials" role="list">
          <a role="listitem" href="https://www.instagram.com/agha.hairdresser" target="_blank" rel="noopener noreferrer">Instagram</a>
          <a role="listitem" href="https://www.tiktok.com/@agha.hairdresser" target="_blank" rel="noopener noreferrer">TikTok</a>
        </div>
      </div>

      <div style="margin-top:14px">
        <a href="tel:07493670608" style="display:inline-block;background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700">Call to book</a>
      </div>
    </aside>

    <footer>
      © Agha hairdresser — Portfolio / Work showcase
    </footer>
  </div>
</body>
</html>
