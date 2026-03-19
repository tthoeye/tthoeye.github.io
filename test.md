<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Open Call 2 – LDT4SSC</title>
<style>
  :root {
    --blue:        #1F75D6;
    --blue-mid:    #5497DC;
    --blue-pale:   #C8DFF5;
    --blue-tint:   #EBF4FD;
    --green:       #29A329;
    --green-mid:   #5AB85A;
    --green-pale:  #C8E8C8;
    --green-tint:  #EDF7E8;
    --yellow:      #F5B400;
    --yellow-pale: #FDE9A0;
    --yellow-tint: #FFFAE8;
    --grey:        #4C5562;
    --grey-mid:    #7D8896;
    --grey-pale:   #E0E3E8;
    --grey-tint:   #F5F6F8;
    --white:       #ffffff;
    --ink:         #1E2530;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: Arial, Helvetica, sans-serif;
    background: var(--white);
    color: var(--grey);
    overflow-x: hidden;
    font-size: 15px;
    line-height: 1.6;
  }

  a { text-decoration: none; color: inherit; }

  /* ── BANNER ── */
  .banner {
    background: var(--yellow);
    color: var(--ink);
    text-align: center;
    padding: 11px 20px;
    font-size: 13.5px;
    font-weight: 700;
    position: sticky;
    top: 0;
    z-index: 200;
    border-bottom: 2px solid #d69e00;
  }

  /* ── LAYOUT ── */
  .wrap { max-width: 1180px; margin: 0 auto; padding: 0 40px; }
  .divider { height: 1px; background: var(--grey-pale); margin: 0 40px; }

  /* ── BUTTONS ── */
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    padding: 12px 22px;
    border-radius: 6px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700;
    transition: filter 0.15s, transform 0.15s;
  }
  .btn:hover { filter: brightness(1.08); transform: translateY(-1px); }
  .btn-blue    { background: var(--blue);   color: #fff; }
  .btn-green   { background: var(--green);  color: #fff; }
  .btn-yellow  { background: var(--yellow); color: var(--ink); }
  .btn-outline {
    background: var(--white);
    border: 2px solid var(--blue);
    color: var(--blue);
  }
  .btn-outline:hover { background: var(--blue-tint); filter: none; }

  /* ── SECTION LABEL ── */
  .sec-label {
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 0.13em;
    text-transform: uppercase;
    color: var(--blue);
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 12px;
  }
  .sec-label::before {
    content: '';
    display: block;
    width: 24px; height: 2px;
    background: var(--blue);
    border-radius: 2px;
    flex-shrink: 0;
  }

  .sec-title {
    font-size: clamp(24px, 3vw, 38px);
    font-weight: 700;
    color: var(--ink);
    letter-spacing: -0.01em;
    line-height: 1.15;
    margin-bottom: 12px;
  }
  .sec-sub {
    font-size: 15px;
    color: var(--grey-mid);
    max-width: 580px;
    line-height: 1.7;
    margin-bottom: 44px;
  }

  /* ── HERO ── */
  .hero { background: var(--blue-tint); border-bottom: 2px solid var(--blue-pale); }
  .hero-inner {
    max-width: 1180px;
    margin: 0 auto;
    padding: 68px 40px 60px;
    display: grid;
    grid-template-columns: 1fr 320px;
    gap: 60px;
    align-items: center;
  }

  .hero-badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: var(--green-pale);
    border: 1.5px solid var(--green);
    color: var(--green);
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 0.07em;
    text-transform: uppercase;
    padding: 5px 13px;
    border-radius: 100px;
    margin-bottom: 22px;
  }
  .hero-badge .dot {
    width: 7px; height: 7px;
    background: var(--green);
    border-radius: 50%;
  }

  .hero h1 {
    font-size: clamp(30px, 4vw, 52px);
    font-weight: 700;
    color: var(--ink);
    line-height: 1.1;
    letter-spacing: -0.01em;
    margin-bottom: 18px;
  }
  .hero h1 .accent { color: var(--blue); }

  .hero-sub {
    font-size: 16px;
    color: var(--grey);
    max-width: 560px;
    line-height: 1.7;
    margin-bottom: 32px;
  }

  .hero-btns { display: flex; gap: 12px; flex-wrap: wrap; margin-bottom: 44px; }

  .hero-stats {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    border: 1.5px solid var(--blue-pale);
    border-radius: 10px;
    overflow: hidden;
    background: var(--white);
  }
  .stat { padding: 18px 20px; border-right: 1.5px solid var(--blue-pale); }
  .stat:last-child { border-right: none; }
  .stat-val { font-size: 26px; font-weight: 700; color: var(--blue); line-height: 1; }
  .stat-lbl { font-size: 11px; color: var(--grey-mid); margin-top: 4px; text-transform: uppercase; letter-spacing: 0.06em; }

  /* Hero diagram */
  .hero-diagram { width: 320px; flex-shrink: 0; }
  .hero-diagram svg { width: 100%; height: auto; display: block; }

  /* ── STRANDS INTRO ── */
  .about-sec { padding: 80px 0; }
  .strands-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 20px; }
  .strand-intro {
    background: var(--grey-tint);
    border: 1.5px solid var(--grey-pale);
    border-top: 4px solid var(--blue);
    border-radius: 10px;
    padding: 32px 28px;
    transition: box-shadow 0.2s;
  }
  .strand-intro:hover { box-shadow: 0 6px 20px rgba(31,117,214,0.10); }
  .strand-num { font-size: 44px; font-weight: 700; color: var(--blue-pale); line-height: 1; margin-bottom: 10px; }
  .strand-intro h3 { font-size: 17px; font-weight: 700; color: var(--ink); margin-bottom: 10px; }
  .strand-intro p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

  /* ── WHY APPLY ── */
  .why-sec {
    background: var(--grey-tint);
    border-top: 1px solid var(--grey-pale);
    border-bottom: 1px solid var(--grey-pale);
    padding: 80px 0;
  }
  .why-grid { display: grid; grid-template-columns: repeat(2,1fr); gap: 18px; }
  .why-card {
    background: var(--white);
    border: 1.5px solid var(--grey-pale);
    border-radius: 10px;
    padding: 28px 24px;
    display: flex;
    gap: 18px;
    align-items: flex-start;
    transition: border-color 0.2s, box-shadow 0.2s;
  }
  .why-card:hover { border-color: var(--blue-mid); box-shadow: 0 4px 16px rgba(31,117,214,0.09); }
  .why-icon {
    width: 44px; height: 44px;
    border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 21px;
    flex-shrink: 0;
  }
  .wi-blue   { background: var(--blue-tint); }
  .wi-green  { background: var(--green-tint); }
  .wi-yellow { background: var(--yellow-tint); }
  .why-body h3 { font-size: 16px; font-weight: 700; color: var(--ink); margin-bottom: 6px; }
  .why-body p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

  /* ── FUNDING + WHO ── */
  .ribbon-sec { padding: 80px 0; }
  .ribbon-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; }

  .funding-card { background: var(--blue); border-radius: 12px; padding: 40px; color: #fff; }
  .funding-card h3 { font-size: 19px; font-weight: 700; margin-bottom: 28px; }
  .funding-items { display: grid; grid-template-columns: 1fr 1fr; gap: 22px; }
  .fi-val { font-size: 26px; font-weight: 700; line-height: 1; }
  .fi-lbl { font-size: 11.5px; opacity: 0.7; margin-top: 4px; text-transform: uppercase; letter-spacing: 0.05em; }

  .who-card {
    background: var(--grey-tint);
    border: 1.5px solid var(--grey-pale);
    border-radius: 12px;
    padding: 40px;
  }
  .who-card h3 { font-size: 19px; font-weight: 700; color: var(--ink); margin-bottom: 24px; }
  .who-tags { display: flex; flex-wrap: wrap; gap: 10px; }
  .who-tag {
    background: var(--white);
    border: 1.5px solid var(--grey-pale);
    color: var(--grey);
    font-size: 13px;
    font-weight: 700;
    padding: 7px 14px;
    border-radius: 100px;
  }

  /* ── TIMELINE ── */
  .timeline-sec {
    background: var(--blue-tint);
    border-top: 1px solid var(--blue-pale);
    border-bottom: 1px solid var(--blue-pale);
    padding: 80px 0;
  }
  .timeline {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    position: relative;
    max-width: 800px;
  }
  .timeline::before {
    content: '';
    position: absolute;
    top: 13px; left: 13px; right: 13px;
    height: 2px;
    background: linear-gradient(90deg, var(--blue), var(--yellow), var(--green));
  }
  .tl-item { position: relative; padding-top: 42px; padding-right: 24px; }
  .tl-dot {
    position: absolute;
    top: 6px; left: 0;
    width: 15px; height: 15px;
    border-radius: 50%;
    border: 3px solid var(--blue-tint);
    z-index: 1;
  }
  .tl-item:nth-child(1) .tl-dot { background: var(--blue); }
  .tl-item:nth-child(2) .tl-dot { background: var(--yellow); border-color: var(--blue-tint); }
  .tl-item:nth-child(3) .tl-dot { background: var(--green); }
  .tl-date { font-size: 11px; font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase; margin-bottom: 6px; }
  .tl-item:nth-child(1) .tl-date { color: var(--blue); }
  .tl-item:nth-child(2) .tl-date { color: #b07f00; }
  .tl-item:nth-child(3) .tl-date { color: var(--green); }
  .tl-title { font-size: 16px; font-weight: 700; color: var(--ink); margin-bottom: 4px; }
  .tl-desc  { font-size: 13px; color: var(--grey-mid); line-height: 1.6; }

  /* ── APPLY ── */
  .apply-sec { padding: 80px 0; }
  .strand-card {
    background: var(--grey-tint);
    border: 1.5px solid var(--grey-pale);
    border-left: 5px solid var(--blue);
    border-radius: 10px;
    padding: 38px 40px 34px;
    margin-bottom: 20px;
    transition: box-shadow 0.2s;
  }
  .strand-card:hover { box-shadow: 0 6px 22px rgba(31,117,214,0.09); }
  .strand-header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 24px;
    margin-bottom: 26px;
    flex-wrap: wrap;
  }
  .strand-tag {
    display: inline-block;
    font-size: 10.5px;
    font-weight: 700;
    letter-spacing: 0.10em;
    text-transform: uppercase;
    background: var(--blue-pale);
    color: var(--blue);
    padding: 4px 11px;
    border-radius: 100px;
    margin-bottom: 10px;
  }
  .strand-card h3 { font-size: 20px; font-weight: 700; color: var(--ink); margin-bottom: 6px; }
  .strand-card .sdesc { font-size: 13.5px; color: var(--grey-mid); line-height: 1.65; max-width: 520px; }

  .doc-grid { display: flex; flex-wrap: wrap; gap: 9px; align-items: center; }
  .doc-pill {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: var(--white);
    border: 1.5px solid var(--grey-pale);
    color: var(--grey);
    padding: 8px 14px;
    border-radius: 6px;
    font-size: 13px;
    font-weight: 700;
    transition: border-color 0.15s, color 0.15s, background 0.15s;
  }
  .doc-pill:hover { border-color: var(--blue); color: var(--blue); background: var(--blue-tint); }

  .submit-pill {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    background: var(--yellow);
    color: var(--ink);
    padding: 11px 20px;
    border-radius: 6px;
    font-size: 13.5px;
    font-weight: 700;
    white-space: nowrap;
    transition: filter 0.15s, transform 0.15s;
  }
  .submit-pill:hover { filter: brightness(1.07); transform: translateY(-1px); }

  /* ── INFO SESSION ── */
  .info-sec {
    background: var(--grey-tint);
    border-top: 1px solid var(--grey-pale);
    border-bottom: 1px solid var(--grey-pale);
    padding: 80px 0;
  }
  .info-inner { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: start; }
  .info-left h2 { font-size: 28px; font-weight: 700; color: var(--ink); margin-bottom: 12px; }
  .info-left p  { font-size: 14.5px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 28px; }
  .info-btns    { display: flex; gap: 12px; flex-wrap: wrap; }

  .glance {
    background: var(--white);
    border: 1.5px solid var(--grey-pale);
    border-radius: 10px;
    overflow: hidden;
  }
  .glance-head {
    background: var(--blue);
    color: #fff;
    padding: 13px 22px;
    font-size: 11.5px;
    font-weight: 700;
    letter-spacing: 0.09em;
    text-transform: uppercase;
  }
  .glance-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 22px;
    border-bottom: 1px solid var(--grey-pale);
    font-size: 14px;
  }
  .glance-row:last-child { border-bottom: none; }
  .gr-key { color: var(--grey-mid); }
  .gr-val { font-weight: 700; color: var(--ink); }
  .gr-val.open   { color: var(--green); }
  .gr-val.urgent { color: #b07f00; }

  /* ── CTA ── */
  .cta-sec { padding: 80px 0; }
  .cta-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; }

  .contact-card {
    background: var(--blue-tint);
    border: 1.5px solid var(--blue-pale);
    border-radius: 12px;
    padding: 44px;
  }
  .contact-card h3 { font-size: 21px; font-weight: 700; color: var(--ink); margin-bottom: 10px; }
  .contact-card p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 28px; }

  .cta-links { display: flex; flex-direction: column; gap: 10px; }
  .cta-link {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 13px 16px;
    background: var(--white);
    border: 1.5px solid var(--blue-pale);
    border-radius: 8px;
    font-size: 14px;
    font-weight: 700;
    color: var(--blue);
    transition: border-color 0.15s, background 0.15s;
  }
  .cta-link:hover { border-color: var(--blue); background: var(--blue-pale); }
  .cl-icon { font-size: 17px; }

  .eval-card {
    background: var(--yellow-tint);
    border: 1.5px solid var(--yellow-pale);
    border-radius: 12px;
    padding: 44px;
    display: flex;
    flex-direction: column;
  }
  .eval-card h3 { font-size: 21px; font-weight: 700; color: var(--ink); margin-bottom: 10px; }
  .eval-card p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 32px; flex: 1; }

  /* ── FOOTER ── */
  .footer {
    background: var(--grey-tint);
    border-top: 1px solid var(--grey-pale);
    padding: 26px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    flex-wrap: wrap;
    font-size: 12px;
    color: var(--grey-mid);
  }

  /* ── RESPONSIVE ── */
  @media (max-width: 900px) {
    .wrap { padding: 0 20px; }
    .hero-inner { grid-template-columns: 1fr; padding: 48px 20px; }
    .hero-diagram { display: none; }
    .strands-grid, .why-grid, .ribbon-grid,
    .timeline, .cta-grid, .info-inner { grid-template-columns: 1fr; }
    .timeline::before { display: none; }
    .tl-item { padding-top: 0; padding-left: 28px; padding-bottom: 24px; }
    .tl-dot { top: 2px; left: 0; }
    .about-sec, .why-sec, .ribbon-sec,
    .timeline-sec, .apply-sec, .info-sec, .cta-sec { padding: 52px 0; }
    .divider { margin: 0 20px; }
    .strand-card { padding: 26px 20px; }
    .strand-header { flex-direction: column; }
    .funding-card, .who-card, .contact-card, .eval-card { padding: 28px; }
    .footer { flex-direction: column; text-align: center; padding: 22px 20px; }
    .hero-stats { grid-template-columns: repeat(3,1fr); }
  }
</style>
</head>
<body>

<!-- BANNER -->
<div class="banner">
  ⚠️ Deadline extended — Submit your application by <strong>15 April 2026 (23:59 CEST)</strong>
</div>

<!-- ══ HERO ══ -->
<div class="hero">
  <div class="hero-inner">
    <div>
      <div class="hero-badge"><span class="dot"></span> Open Call 2 · Status: Open</div>
      <h1>Build the <span class="accent">European</span><br>Digital Twin Network</h1>
      <p class="hero-sub">
        The LDT4SSC project, funded by the Digital Europe Programme, invites cities, organisations, SMEs, researchers and innovators to apply for its second round of open calls.
      </p>
      <div class="hero-btns">
        <a href="https://ldt4ssc.eu/documents/infosession2.pdf" class="btn btn-blue">↓ Download Slides</a>
        <a href="https://youtu.be/Ou3HtJf_R68?si=rM8vHhfYG4UjQrTG" class="btn btn-green">▶ Watch Webinar</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><div class="stat-val">€17M</div><div class="stat-lbl">Total Funding</div></div>
        <div class="stat"><div class="stat-val">€1M</div><div class="stat-lbl">Max / Consortium</div></div>
        <div class="stat"><div class="stat-val">18 mo</div><div class="stat-lbl">Max Duration</div></div>
      </div>
    </div>

    <!-- Static network diagram -->
    <div class="hero-diagram">
      <svg viewBox="0 0 320 330" xmlns="http://www.w3.org/2000/svg">
        <circle cx="160" cy="155" r="148" fill="#D6E8F8" stroke="#B8D5F2" stroke-width="1"/>
        <circle cx="160" cy="155" r="118" fill="none" stroke="#B8D5F2" stroke-width="1" stroke-dasharray="5 8"/>
        <!-- Lines -->
        <g stroke="#5497DC" stroke-width="1.5" opacity="0.5">
          <line x1="160" y1="155" x2="82"  y2="62"/>
          <line x1="160" y1="155" x2="238" y2="62"/>
          <line x1="160" y1="155" x2="58"  y2="192"/>
          <line x1="160" y1="155" x2="262" y2="192"/>
          <line x1="160" y1="155" x2="124" y2="262"/>
          <line x1="160" y1="155" x2="196" y2="262"/>
          <line x1="82"  y1="62"  x2="238" y2="62"  stroke="#5AB85A" stroke-width="1" opacity="0.5"/>
          <line x1="58"  y1="192" x2="124" y2="262" stroke="#5AB85A" stroke-width="1" opacity="0.5"/>
          <line x1="262" y1="192" x2="196" y2="262" stroke="#5AB85A" stroke-width="1" opacity="0.5"/>
        </g>
        <!-- Nodes -->
        <circle cx="82"  cy="62"  r="20" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="82"  y="67"  text-anchor="middle" font-family="Arial" font-size="9.5" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="238" cy="62"  r="20" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="238" y="67"  text-anchor="middle" font-family="Arial" font-size="9.5" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="58"  cy="192" r="20" fill="#EDF7E8" stroke="#29A329" stroke-width="2"/>
        <text   x="58"  y="197" text-anchor="middle" font-family="Arial" font-size="9.5" font-weight="700" fill="#29A329">DT</text>
        <circle cx="262" cy="192" r="20" fill="#EDF7E8" stroke="#29A329" stroke-width="2"/>
        <text   x="262" y="197" text-anchor="middle" font-family="Arial" font-size="9.5" font-weight="700" fill="#29A329">DT</text>
        <circle cx="124" cy="262" r="20" fill="#FFFAE8" stroke="#F5B400" stroke-width="2"/>
        <text   x="124" y="267" text-anchor="middle" font-family="Arial" font-size="9.5" font-weight="700" fill="#b07f00">AI</text>
        <circle cx="196" cy="262" r="20" fill="#FFFAE8" stroke="#F5B400" stroke-width="2"/>
        <text   x="196" y="267" text-anchor="middle" font-family="Arial" font-size="9.5" font-weight="700" fill="#b07f00">AI</text>
        <!-- Centre -->
        <circle cx="160" cy="155" r="34" fill="#D6E8F8"/>
        <circle cx="160" cy="155" r="24" fill="#1F75D6" stroke="#fff" stroke-width="2.5"/>
        <text   x="160" y="159" text-anchor="middle" font-family="Arial" font-size="11" font-weight="700" fill="#fff">EU</text>
        <!-- Legend -->
        <g font-family="Arial" font-size="10.5" fill="#4C5562">
          <circle cx="14" cy="305" r="5" fill="#1F75D6"/>
          <text x="24" y="309">Strand 1 – Connect</text>
          <circle cx="14" cy="320" r="5" fill="#29A329"/>
          <text x="24" y="324">Strand 2 – Create</text>
          <circle cx="168" cy="305" r="5" fill="#F5B400"/>
          <text x="178" y="309">Strand 3 – AI</text>
        </g>
      </svg>
    </div>
  </div>
</div>

<div class="divider"></div>

<!-- ══ WHAT IS OC2 ══ -->
<section class="about-sec">
  <div class="wrap">
    <div class="sec-label">Open Call 2</div>
    <h2 class="sec-title">Three Work Strands, One European Mission</h2>
    <p class="sec-sub">Open Call 2 invites applications for all three work strands — interconnecting, creating and enhancing Local Digital Twins across Europe.</p>
    <div class="strands-grid">
      <div class="strand-intro">
        <div class="strand-num">01</div>
        <h3>Interconnect &amp; Federate</h3>
        <p>Inter-connection of existing Local Digital Twins to form a European-scale federated, interoperable network enabling cross-border data exchange and multi-city optimisation.</p>
      </div>
      <div class="strand-intro">
        <div class="strand-num">02</div>
        <h3>Create New Local Digital Twins</h3>
        <p>Creation of new Local Digital Twins based on shared challenges across cities and communities — from climate resilience to smart mobility.</p>
      </div>
      <div class="strand-intro">
        <div class="strand-num">03</div>
        <h3>Add Advanced AI Capabilities</h3>
        <p>Adding advanced AI-based capabilities and innovative open-source components to the EU LDT Toolbox — simulation, prediction and optimisation.</p>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ WHY APPLY ══ -->
<section class="why-sec">
  <div class="wrap">
    <div class="sec-label">Benefits</div>
    <h2 class="sec-title">Why apply?</h2>
    <div class="why-grid">
      <div class="why-card">
        <div class="why-icon wi-blue">🌐</div>
        <div class="why-body">
          <h3>Interconnect &amp; Federate</h3>
          <p>Link your Local Digital Twins with other European cities to form a federated, interoperable network enabling cross-border data exchange and multi-city optimisation.</p>
        </div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-yellow">💶</div>
        <div class="why-body">
          <h3>Secure Financial Support</h3>
          <p>With a €17 million funding pot, de-risk innovation and deploy high-impact digital services without carrying the full financial burden alone.</p>
        </div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-blue">🧰</div>
        <div class="why-body">
          <h3>Access the EU LDT Toolbox</h3>
          <p>Use open-source specifications, reference architectures and certified AI tools that are standard-based and deployment-ready across Europe.</p>
        </div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-green">🤖</div>
        <div class="why-body">
          <h3>Deploy Advanced AI Services</h3>
          <p>Simulate future scenarios in areas like climate resilience and smart mobility before making real-world investments — with confidence.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══ FUNDING + WHO ══ -->
<section class="ribbon-sec">
  <div class="wrap">
    <div class="ribbon-grid">
      <div class="funding-card">
        <h3>💰 What can you get?</h3>
        <div class="funding-items">
          <div><div class="fi-val">€1,000,000</div><div class="fi-lbl">Max per consortium</div></div>
          <div><div class="fi-val">50%</div><div class="fi-lbl">Co-funding required</div></div>
          <div><div class="fi-val">€500,000</div><div class="fi-lbl">Max per third party</div></div>
          <div><div class="fi-val">12–18 mo</div><div class="fi-lbl">Project duration</div></div>
        </div>
      </div>
      <div class="who-card">
        <h3>👥 Who can apply?</h3>
        <div class="who-tags">
          <span class="who-tag">🏛 Local authorities</span>
          <span class="who-tag">🏙 Regional authorities</span>
          <span class="who-tag">🏢 National authorities</span>
          <span class="who-tag">🏗 Private organisations</span>
          <span class="who-tag">🚀 SMEs</span>
          <span class="who-tag">🤝 NGOs</span>
          <span class="who-tag">🔬 Research institutions</span>
          <span class="who-tag">🎓 Academia</span>
          <span class="who-tag">🌱 Not-for-profits</span>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ TIMELINE ══ -->
<section class="timeline-sec">
  <div class="wrap">
    <div class="sec-label">Key Dates</div>
    <h2 class="sec-title" style="margin-bottom:44px;">What to remember?</h2>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">02 February 2026</div>
        <div class="tl-title">Open Call Launched</div>
        <div class="tl-desc">Application portal opens; all documents available for download</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">15 April 2026 · 23:59 CEST</div>
        <div class="tl-title">Submission Deadline</div>
        <div class="tl-desc">All applications must be submitted to applications@ldt4ssc.eu</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">31 August 2026</div>
        <div class="tl-title">Pilot Start</div>
        <div class="tl-desc">Selected consortia begin their implementation phase</div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ HOW TO APPLY ══ -->
<section class="apply-sec">
  <div class="wrap">
    <div class="sec-label">Applications</div>
    <h2 class="sec-title">How to apply</h2>
    <p class="sec-sub">Prepare and submit all required documents per work strand to <strong>applications@ldt4ssc.eu</strong></p>

    <!-- Strand 1 -->
    <div class="strand-card">
      <div class="strand-header">
        <div>
          <span class="strand-tag">Work Strand 01</span>
          <h3>Interconnecting Existing Local Digital Twins</h3>
          <p class="sdesc">Ensure all documents are completed, signed, eligibility criteria met and alignment with Work Strand 1 objectives.</p>
        </div>
        <a href="mailto:applications@ldt4ssc.eu" class="submit-pill">✉ Submit Application</a>
      </div>
      <div class="doc-grid">
        <a href="https://ldt4ssc.eu/documents/cpmws1.pdf"  class="doc-pill">📄 Pilot Manual</a>
        <a href="https://ldt4ssc.eu/documents/afws1.docx"  class="doc-pill">📝 Application Form</a>
        <a href="https://ldt4ssc.eu/documents/locws1.docx" class="doc-pill">📋 Letter of Commitment</a>
        <a href="https://ldt4ssc.eu/documents/ocd1.docx"   class="doc-pill">🔏 Ownership Declaration</a>
        <a href="https://ldt4ssc.eu/documents/financial_form.xlsx" class="doc-pill">💹 Financial Form</a>
        <a href="https://ldt4ssc.eu/documents/ethics_and_data_protection_assessment.xlsx" class="doc-pill">⚖️ Ethics Assessment</a>
      </div>
    </div>

    <!-- Strand 2 -->
    <div class="strand-card">
      <div class="strand-header">
        <div>
          <span class="strand-tag">Work Strand 02</span>
          <h3>Creating New Local Digital Twins Based on Common Needs</h3>
          <p class="sdesc">Ensure all documents are completed, signed, eligibility criteria met and alignment with Work Strand 2 objectives.</p>
        </div>
        <a href="mailto:applications@ldt4ssc.eu" class="submit-pill">✉ Submit Application</a>
      </div>
      <div class="doc-grid">
        <a href="https://ldt4ssc.eu/documents/cpmws2.pdf"  class="doc-pill">📄 Pilot Manual</a>
        <a href="https://ldt4ssc.eu/documents/afws2.docx"  class="doc-pill">📝 Application Form</a>
        <a href="https://ldt4ssc.eu/documents/locws2.docx" class="doc-pill">📋 Letter of Commitment</a>
        <a href="https://ldt4ssc.eu/documents/loiws2.docx" class="doc-pill">🤝 Letter of Intent</a>
        <a href="https://ldt4ssc.eu/documents/ocd2.docx"   class="doc-pill">🔏 Ownership Declaration</a>
        <a href="https://ldt4ssc.eu/documents/financial_form.xlsx" class="doc-pill">💹 Financial Form</a>
        <a href="https://ldt4ssc.eu/documents/ethics_and_data_protection_assessment.xlsx" class="doc-pill">⚖️ Ethics Assessment</a>
      </div>
    </div>

    <!-- Strand 3 -->
    <div class="strand-card">
      <div class="strand-header">
        <div>
          <span class="strand-tag">Work Strand 03</span>
          <h3>Adding New Advanced AI-Based Capabilities to the LDT Toolbox</h3>
          <p class="sdesc">Ensure all documents are completed, signed, eligibility criteria met and alignment with Work Strand 3 objectives.</p>
        </div>
        <a href="mailto:applications@ldt4ssc.eu" class="submit-pill">✉ Submit Application</a>
      </div>
      <div class="doc-grid">
        <a href="https://ldt4ssc.eu/documents/cpmws3.pdf"  class="doc-pill">📄 Pilot Manual</a>
        <a href="https://ldt4ssc.eu/documents/afws3.docx"  class="doc-pill">📝 Application Form</a>
        <a href="https://ldt4ssc.eu/documents/locws3.docx" class="doc-pill">📋 Letter of Commitment</a>
        <a href="https://ldt4ssc.eu/documents/ocd3.docx"   class="doc-pill">🔏 Ownership Declaration</a>
        <a href="https://ldt4ssc.eu/documents/financial_form.xlsx" class="doc-pill">💹 Financial Form</a>
        <a href="https://ldt4ssc.eu/documents/ethics_and_data_protection_assessment.xlsx" class="doc-pill">⚖️ Ethics Assessment</a>
      </div>
    </div>
  </div>
</section>

<!-- ══ INFO SESSION ══ -->
<section class="info-sec">
  <div class="wrap">
    <div class="info-inner">
      <div class="info-left">
        <div class="sec-label" style="margin-bottom:10px;">Resources</div>
        <h2>Info Session Materials</h2>
        <p>Below you can find all materials from the Open Call 2 Info Session, including the slides and the full recording of the webinar.</p>
        <div class="info-btns">
          <a href="https://ldt4ssc.eu/documents/infosession2.pdf" class="btn btn-blue">↓ Download Slides</a>
          <a href="https://youtu.be/Ou3HtJf_R68?si=rM8vHhfYG4UjQrTG" class="btn btn-outline">▶ Watch Recording</a>
        </div>
      </div>
      <div class="glance">
        <div class="glance-head">Call at a glance</div>
        <div class="glance-row"><span class="gr-key">Status</span><span class="gr-val open">● Open</span></div>
        <div class="glance-row"><span class="gr-key">Programme</span><span class="gr-val">Digital Europe (DEP)</span></div>
        <div class="glance-row"><span class="gr-key">Total funding</span><span class="gr-val">€17,000,000</span></div>
        <div class="glance-row"><span class="gr-key">Max per consortium</span><span class="gr-val">€1,000,000</span></div>
        <div class="glance-row"><span class="gr-key">Co-funding required</span><span class="gr-val">50%</span></div>
        <div class="glance-row"><span class="gr-key">Submission deadline</span><span class="gr-val urgent">15 Apr 2026</span></div>
        <div class="glance-row"><span class="gr-key">Pilot start</span><span class="gr-val">31 Aug 2026</span></div>
      </div>
    </div>
  </div>
</section>

<!-- ══ CTA ══ -->
<section class="cta-sec">
  <div class="wrap">
    <div class="cta-grid">
      <div class="contact-card">
        <div class="sec-label" style="margin-bottom:10px;">Get Involved</div>
        <h3>Learn more, ask questions or join a consortium</h3>
        <p>Reach out to the LDT4SSC team, find consortium partners via the matchmaking platform, join an upcoming info session or subscribe for updates.</p>
        <div class="cta-links">
          <a href="mailto:info@ldt4ssc.eu" class="cta-link">
            <span class="cl-icon">✉</span> Email us — info@ldt4ssc.eu
          </a>
          <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="cta-link">
            <span class="cl-icon">🤝</span> Find partners via the Matchmaking Platform
          </a>
          <a href="https://ldt4ssc.eu/services/webinar3/" class="cta-link">
            <span class="cl-icon">🎥</span> Join the info session
          </a>
          <a href="https://shorturl.at/pzMGK" class="cta-link">
            <span class="cl-icon">📬</span> Subscribe to the newsletter
          </a>
        </div>
      </div>
      <div class="eval-card">
        <div class="sec-label" style="margin-bottom:10px; color:#b07f00;">
          <span style="width:24px;height:2px;background:#b07f00;display:inline-block;border-radius:2px;"></span>
          Evaluators
        </div>
        <h3>Apply as an Evaluator</h3>
        <p>Are you an expert in digital twins, smart cities, AI or urban planning? LDT4SSC is looking for qualified evaluators to assess Open Call 2 applications. Contribute your expertise to shape Europe's digital twin ecosystem.</p>
        <a href="https://ldt4ssc.eu/call-evaluators/" class="btn btn-yellow">Learn More →</a>
      </div>
    </div>
  </div>
</section>

<!-- ══ FOOTER ══ -->
<footer class="footer">
  <span>LDT4SSC — Grant Agreement No. 101226211 · Digital Europe Programme</span>
  <span>Views expressed are those of the author(s) only and do not necessarily reflect those of the EU or the European Commission.</span>
</footer>

</body>
</html>
