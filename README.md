# q
a
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Per saperne di più — Margarita Salas</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: Arial, sans-serif;
      background: #ffffff;
    }

    .wrap {
      max-width: 860px;
      margin: 0 auto;
      padding: 56px 32px;
    }

    .section-title {
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: #0C447C;
      margin-bottom: 18px;
      border-top: 1px solid #B5D4F4;
      padding-top: 22px;
    }

    /* --- Box motivazionale --- */
    .cta-box {
      background: #042C53;
      border-radius: 14px;
      padding: 32px;
      margin-bottom: 24px;
      text-align: center;
    }

    .cta-title {
      font-size: 22px;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 12px;
      font-family: Georgia, serif;
      line-height: 1.4;
    }

    .cta-text {
      font-size: 15px;
      color: #9FC6E8;
      line-height: 1.8;
      max-width: 540px;
      margin: 0 auto;
    }

    /* --- Griglia link --- */
    .links-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 14px;
      margin-bottom: 20px;
    }

    .link-card {
      border: 1px solid #B5D4F4;
      border-radius: 10px;
      padding: 16px 18px;
      display: flex;
      gap: 14px;
      align-items: flex-start;
      text-decoration: none;
      transition: background 0.2s;
    }

    .link-card:hover {
      background: #E6F1FB;
    }

    .link-icon {
      width: 40px;
      height: 40px;
      border-radius: 8px;
      background: #E6F1FB;
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .link-icon svg {
      width: 20px;
      height: 20px;
    }

    .link-title {
      font-size: 13px;
      font-weight: 700;
      color: #042C53;
      margin-bottom: 4px;
    }

    .link-desc {
      font-size: 12px;
      color: #185FA5;
      line-height: 1.55;
    }

    .link-url {
      font-size: 11px;
      color: #aaaaaa;
      margin-top: 5px;
    }

    .footer-note {
      margin-top: 24px;
      font-size: 12px;
      color: #aaaaaa;
      text-align: center;
      font-style: italic;
    }

    @media (max-width: 600px) {
      .wrap { padding: 36px 16px; }
      .cta-title { font-size: 18px; }
      .links-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

<div class="wrap">

  <p class="section-title">Per saperne di più</p>

  <!-- Box motivazionale -->
  <div class="cta-box">
    <p class="cta-title">La scienza non si ferma mai — e neanche tu</p>
    <p class="cta-text">Margarita Salas ha dimostrato che la curiosità, la perseveranza e la passione per la ricerca possono cambiare il mondo. Approfondisci la sua storia e lasciati ispirare.</p>
  </div>

  <!-- Griglia link -->
  <div class="links-grid">

    <a class="link-card" href="https://www.nobelprize.org/prizes/medicine/1959/ochoa/biographical/" target="_blank">
      <div class="link-icon">
        <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="10" cy="10" r="8" stroke="#185FA5" stroke-width="1.8"/>
          <path d="M10 6v5l3 1.5" stroke="#185FA5" stroke-width="1.8" stroke-linecap="round"/>
        </svg>
      </div>
      <div>
        <p class="link-title">Severo Ochoa — Nobel Prize</p>
        <p class="link-desc">Scopri la biografia del mentore di Margarita, premio Nobel per la Medicina 1959.</p>
        <p class="link-url">nobelprize.org</p>
      </div>
    </a>

    <a class="link-card" href="https://www.epo.org/en/news-events/european-inventor-award/2019-finalists-and-winners/salas" target="_blank">
      <div class="link-icon">
        <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M10 2l2.5 5.5 6 .9-4.3 4.2 1 6L10 16l-5.2 2.6 1-6L1.5 8.4l6-.9z" fill="#185FA5"/>
        </svg>
      </div>
      <div>
        <p class="link-title">Premio Europeo dell'Inventore</p>
        <p class="link-desc">Il riconoscimento lifetime achievement ricevuto da Margarita Salas nel 2019.</p>
        <p class="link-url">epo.org</p>
      </div>
    </a>

    <a class="link-card" href="https://it.wikipedia.org/wiki/Margarita_Salas" target="_blank">
      <div class="link-icon">
        <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect x="3" y="3" width="14" height="14" rx="2" stroke="#185FA5" stroke-width="1.8"/>
          <path d="M6 8h8M6 11h5" stroke="#185FA5" stroke-width="1.8" stroke-linecap="round"/>
        </svg>
      </div>
      <div>
        <p class="link-title">Wikipedia — Margarita Salas</p>
        <p class="link-desc">Voce enciclopedica completa sulla vita, le scoperte e i riconoscimenti della scienziata.</p>
        <p class="link-url">it.wikipedia.org</p>
      </div>
    </a>

    <a class="link-card" href="https://www.csic.es" target="_blank">
      <div class="link-icon">
        <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="10" cy="10" r="8" stroke="#185FA5" stroke-width="1.8"/>
          <path d="M6 14c0-2.21 1.79-4 4-4s4 1.79 4 4" stroke="#185FA5" stroke-width="1.8" stroke-linecap="round"/>
          <circle cx="10" cy="7" r="2" fill="#185FA5"/>
        </svg>
      </div>
      <div>
        <p class="link-title">CSIC — Ente di ricerca spagnolo</p>
        <p class="link-desc">Il centro dove Margarita ha lavorato tutta la vita e dove il suo laboratorio è ancora attivo.</p>
        <p class="link-url">csic.es</p>
      </div>
    </a>

  </div>

  <p class="footer-note">Pagina realizzata a scopo didattico · Fonti: Wikipedia, EPO, CSIC, Nobel Prize Organization</p>

</div>

</body>
</html>
