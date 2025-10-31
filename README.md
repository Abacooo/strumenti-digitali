<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Strumenti digitali scolastici</title>
  <style>
    :root {
      --bg: #f8fafc;
      --card: #ffffff;
      --border: #e5e7eb;
      --text: #0f172a;
      --accent: #2563eb;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;background:var(--bg);color:var(--text);padding:24px;display:flex;justify-content:center}
    main{max-width:900px;width:100%}
    h1{font-size:clamp(28px,4vw,40px);margin-bottom:8px;text-align:center}
    p.subtitle{text-align:center;color:#475569;margin-bottom:32px}
    .grid{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
    .card{background:var(--card);border:1px solid var(--border);border-radius:16px;padding:24px;display:flex;flex-direction:column;align-items:flex-start;transition:all .2s ease}
    .card:hover{transform:translateY(-3px);box-shadow:0 4px 12px rgba(0,0,0,.08)}
    .card h2{font-size:20px;margin-bottom:8px}
    .card p{flex:1;font-size:15px;color:#475569;margin-bottom:12px}
    a.btn{border:1px solid var(--border);background:#fff;padding:8px 12px;border-radius:10px;text-decoration:none;color:var(--accent);font-weight:600}
    footer{text-align:center;margin-top:32px;color:#94a3b8;font-size:14px}
  </style>
</head>
<body>
  <main>
    <h1>Strumenti digitali scolastici</h1>
    <p class="subtitle">Cliccate su uno strumento per aprirlo</p>

    <section class="grid">
      <article class="card">
        <h2>🧮 Abaco digitale</h2>
        <p>Visualizza le unità, decine, centinaia e migliaia con perline colorate. Include riporto automatico e modalità schermo intero.</p>
        <a class="btn" href="./abaco/">Apri Abaco</a>
      </article>

      <article class="card">
        <h2>📏 Linea dei numeri</h2>
        <p>Linea interattiva per contare, zoomare e scorrere i numeri in modo visivo. Ideale per la scuola primaria.</p>
        <a class="btn" href="./linea-numeri/">Apri Linea dei numeri</a>
      </article>
    </section>

    <footer>
      © 2025 · Raccolta di strumenti didattici digitali
    </footer>
  </main>
</body>
</html>
