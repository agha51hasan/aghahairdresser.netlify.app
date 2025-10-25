<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Agha hairdresser — Hair • Colour • Balayage • Extensions</title>
  <meta name="description" content="Agha hairdresser — 13 years experience. Specialising in hair up, colour, balayage, haircut, extensions and hair treatments. Located at 60 Baker Street, W1U 7DE." />

  <style>
    :root{
      --bg:#fff;
      --card:#ffffff;
      --muted:#666;
      --accent:#b86b2e; /* warm caramel/honey accent */
      --accent-dark:#8c4e22;
      --border:#eee;
      --max-width:1100px;
      --radius:10px;
      --shadow: 0 6px 18px rgba(20,20,20,0.06);
      font-family: Inter, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
      color:#222;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg, #fff 0%, #fffefc 100%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:32px 16px;
      display:flex;
      justify-content:center;
      font-size:16px;
      line-height:1.45;
    }
    .container{
      width:100%;
      max-width:var(--max-width);
    }

    header.site-header{
      display:flex;
      align-items:center;
      gap:18px;
      margin-bottom:22px;
    }
    .logo{
      width:92px;
      height:92px;
      border-radius:12px;
      background:linear-gradient(135deg, rgba(184,107,46,0.12), rgba(184,107,46,0.03));
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      color:var(--accent-dark);
      font-size:20px;
      border:1px solid var(--border);
      box-shadow:var(--shadow);
    }
    .brand h1{
      margin:0;
      font-size:24px;
      letter-spacing:0.2px;
    }
    .brand p{ margin:6px 0 0; color:var(--muted); }

    main{
      display:grid;
      grid-template-columns: 1fr 360px;
      gap:26px;
      align-items:start;
    }

    /* Left column */
    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:18px;
      box-shadow:var(--shadow);
      border:1px solid var(--border);
    }

    .intro{
      display:flex;
      gap:18px;
      align-items:flex-start;
    }
    .experience{
      font-weight:600;
      color:var(--accent-dark);
      margin-bottom:8px;
    }
    .specialties{
      display:flex;
      flex-wrap:wrap;
      gap:8px;
      margin-top:12px;
    }
    .chip{
      background:linear-gradient(180deg,#fff,#fffefc);
      border:1px solid #f1e7df;
      padding:6px 10px;
      border-radius:999px;
      font-size:14px;
      color:#5a3b2a;
    }

    h2.section-title{
      margin:0 0 14px 0;
      font-size:18px;
      color:#1f1f1f;
    }

    /* Services tables */
    .services-grid{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:12px;
    }
    .services-grid .service-group{
      padding:12px;
      border-radius:8px;
      background:linear-gradient(180deg,#ffffff,#fffdfa);
      border:1px solid var(--border);
    }
    table{
      width:100%;
      border-collapse:collapse;
      margin-top:8px;
      font-size:15px;
    }
    table td, table th{
      padding:8px 6px;
      border-bottom:1px dashed #f0ece9;
      text-align:left;
      vertical-align:middle;
    }
    table td.price { text-align:right; font-weight:600; color:var(--accent-dark); width:110px; }

    /* Right column (contact) */
    aside.contact-card{
      position:sticky;
      top:28px;
    }
    .address p, .contact-links a{
      margin:6px 0;
      color:var(--muted);
      text-decoration:none;
      display:block;
    }
    .phones a{
      color:var(--accent-dark);
      font-weight:600;
      text-decoration:none;
    }
    .social-links{
      display:flex;
      gap:8px;
      margin-top:8px;
    }
    .social-links a{
      padding:8px 10px;
      border-radius:8px;
      border:1px solid #f0e6df;
      text-decoration:none;
      color:#222;
      font-weight:600;
      font-size:14px;
      display:inline-flex;
      align-items:center;
      gap:8px;
    }

    /* footer */
    footer{
      margin-top:20px;
      color:var(--muted);
      font-size:14px;
      text-align:center;
    }

    /* responsive */
    @media (max-width:980px){
      main{ grid-template-columns: 1fr; }
      aside.contact-card{ position:relative; top:auto; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="site-header">
      <div class="logo" aria-hidden="true">AH</div>
      <div class="brand">
        <h1>Agha hairdresser</h1>
        <p>13 years of experience • Specialist in hair up, colour, balayage, haircut, extensions & treatments</p>
      </div>
    </header>

    <main>
      <!-- LEFT: details + services -->
      <section>
        <article class="card intro">
          <div style="flex:1">
            <div class="experience">13 years of professional experience</div>
            <p style="margin:0;color:var(--muted)">
              Agha hairdresser specialises in elegant hair ups, bespoke colour work, modern balayage, precision haircuts, hair extensions and nourishing hair treatments.
            </p>

            <div class="specialties" aria-hidden="false" style="margin-top:14px">
              <span class="chip">Hair Up</span>
              <span class="chip">Colour</span>
              <span class="chip">Balayage</span>
              <span class="chip">Haircut</span>
              <span class="chip">Hair Extensions</span>
              <span class="chip">Hair Treatments</span>
            </div>
          </div>
        </article>

        <article class="card" style="margin-top:16px;">
          <h2 class="section-title">Services & Prices</h2>

          <div class="services-grid">
            <div class="service-group">
              <strong>Styling & Cuts</strong>
              <table aria-label="Styling and cuts">
                <tbody>
                  <tr><td>Blow dry</td><td class="price">£40</td></tr>
                  <tr><td>Hair cut</td><td class="price">£50</td></tr>
                  <tr><td>Haircut and blowdry</td><td class="price">£85</td></tr>
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
              <table aria-label="Hair extensions">
                <tbody>
                  <tr><td>Tap-in (retap)</td><td class="price">£239</td></tr>
                  <tr><td>Extensions sews</td><td class="price">£215</td></tr>
                  <tr><td>Micro-rings</td><td class="price">£215</td></tr>
                  <tr><td>Pre-bonded</td><td class="price">£215</td></tr>
                </tbody>
              </table>
            </div>
          </div>
        </article>

        <footer style="margin-top:14px">
          <div style="font-size:14px;color:var(--muted)">
            For appointments, please call or message. Walk-ins may be available depending on schedule.
          </div>
        </footer>
      </section>

      <!-- RIGHT: contact -->
      <aside class="card contact-card">
        <h2 class="section-title">Contact</h2>

        <div class="address" aria-label="Address">
          <strong>60 Baker Street</strong>
          <p>W1U 7DE</p>
        </div>

        <div class="phones" style="margin-top:12px">
          <div style="font-weight:600;color:var(--accent-dark)">Phone</div>
          <p><a href="tel:07493670608">07493 670608</a></p>
        </div>

        <div style="margin-top:12px" class="contact-links">
          <div style="font-weight:600;color:var(--accent-dark)">Social</div>
          <div class="social-links" role="list">
            <a role="listitem" href="https://www.instagram.com/agha.hairdresser" target="_blank" rel="noopener noreferrer">Instagram</a>
            <a role="listitem" href="https://www.tiktok.com/@agha.hairdresser" target="_blank" rel="noopener noreferrer">TikTok</a>
          </div>
        </div>

        <div style="margin-top:14px; font-size:14px; color:var(--muted)">
          <strong>Opening hours</strong>
          <p style="margin:6px 0 0;">(Please call or check social for current opening hours and availability.)</p>
        </div>

        <div style="margin-top:16px">
          <a href="tel:07493670608" style="display:inline-block;background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700">Call to book</a>
        </div>
      </aside>
    </main>
  </div>
</body>
</html>
