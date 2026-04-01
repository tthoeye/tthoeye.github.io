---
layout: fullwidth
permalink: /call-one/
banner: /images/banner-call-one.jpg
---

<style>
/* ── Break out of col-md-8 ── */
.oc2-escape {
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  width: 100vw;
}

/* ── Scope ── */
.oc2 {
  font-family: Arial, Helvetica, sans-serif;
  color: #4C5562;
  font-size: 15px;
  line-height: 1.6;
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 32px;
}
.oc2 *, .oc2 *::before, .oc2 *::after { box-sizing: border-box; margin: 0; padding: 0; }
.oc2 a { text-decoration: none; color: inherit; }
.oc2 p { margin: 0; }

/* Variables */
.oc2 {
  --blue:        #1F75D6;
  --blue-mid:    #5497DC;
  --blue-pale:   #C8DFF5;
  --blue-tint:   #EBF4FD;
  --green:       #29A329;
  --green-pale:  #C8E8C8;
  --green-tint:  #EDF7E8;
  --yellow:      #F5B400;
  --yellow-pale: #FDE9A0;
  --yellow-tint: #FFFAE8;
  --red:         #D9534F;
  --red-pale:    #F5CCCB;
  --red-tint:    #FDF0EF;
  --grey:        #4C5562;
  --grey-mid:    #7D8896;
  --grey-pale:   #E0E3E8;
  --grey-tint:   #F5F6F8;
  --ink:         #1E2530;
}

/* ── SECTION LABEL ── */
.oc2 .sec-label {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.13em;
  text-transform: uppercase;
  color: var(--blue);
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 10px;
}
.oc2 .sec-label::before {
  content: '';
  display: block;
  width: 22px; height: 2px;
  background: var(--blue);
  border-radius: 2px;
  flex-shrink: 0;
}
.oc2 .sec-title {
  font-size: clamp(22px, 2.8vw, 34px);
  font-weight: 700;
  color: var(--ink);
  line-height: 1.15;
  margin-bottom: 10px;
}
.oc2 .sec-sub {
  font-size: 15px;
  color: var(--grey-mid);
  line-height: 1.7;
  margin-bottom: 28px;
}
.oc2 .sec-divider {
  height: 1px;
  background: var(--grey-pale);
  margin: 8px 0 32px;
}

/* ── BUTTONS ── */
.oc2 .btn {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  padding: 11px 20px;
  border-radius: 6px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 14px;
  font-weight: 700;
  transition: filter 0.15s, transform 0.15s;
  cursor: pointer;
  line-height: 1;
}
.oc2 .btn:hover { filter: brightness(1.08); transform: translateY(-1px); }
.oc2 .btn-blue   { background: var(--blue);   color: #fff !important; }
.oc2 .btn-green  { background: var(--green);  color: #fff !important; }
.oc2 .btn-yellow { background: var(--yellow); color: var(--ink) !important; }
.oc2 .btn-outline {
  background: #fff;
  border: 2px solid var(--blue);
  color: var(--blue) !important;
}
.oc2 .btn-outline:hover { background: var(--blue-tint); filter: none; }

/* ── HERO ── */
.oc2 .hero {
  background: var(--red-tint);
  border: 1.5px solid var(--red-pale);
  border-radius: 14px;
  padding: 48px;
  display: grid;
  grid-template-columns: 1fr 260px;
  gap: 48px;
  align-items: center;
  margin-bottom: 40px;
}
.oc2 .hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: var(--red-pale);
  border: 1.5px solid var(--red);
  color: var(--red);
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  padding: 5px 12px;
  border-radius: 100px;
  margin-bottom: 18px;
}
.oc2 .hero-badge .dot {
  width: 7px; height: 7px;
  background: var(--red);
  border-radius: 50%;
}
.oc2 .hero h1 {
  font-family: Arial, Helvetica, sans-serif !important;
  font-size: clamp(26px, 3vw, 44px) !important;
  font-weight: 700 !important;
  color: var(--ink) !important;
  line-height: 1.1 !important;
  margin-bottom: 16px !important;
  border: none !important;
  padding: 0 !important;
}
.oc2 .hero h1 .accent { color: var(--blue); }
.oc2 .hero-sub {
  font-size: 15px;
  color: var(--grey);
  line-height: 1.7;
  margin-bottom: 28px;
}
.oc2 .hero-btns { display: flex; gap: 12px; flex-wrap: wrap; margin-bottom: 32px; }
.oc2 .hero-stats {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  border: 1.5px solid var(--red-pale);
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
}
.oc2 .stat { padding: 16px 18px; border-right: 1.5px solid var(--red-pale); }
.oc2 .stat:last-child { border-right: none; }
.oc2 .stat-val { font-size: 24px; font-weight: 700; color: var(--red); line-height: 1; }
.oc2 .stat-lbl { font-size: 11px; color: var(--grey-mid); margin-top: 3px; text-transform: uppercase; letter-spacing: 0.06em; }

/* Hero diagram */
.oc2 .hero-diagram svg { width: 100%; height: auto; display: block; }

/* ── BLOCK ── */
.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); }
.oc2 .block-blue { background: var(--blue-tint); border: 1.5px solid var(--blue-pale); }
.oc2 .block-red  { background: var(--red-tint);  border: 1.5px solid var(--red-pale); }

/* ── WHY CARDS ── */
.oc2 .why-grid { display: grid; grid-template-columns: repeat(2,1fr); gap: 16px; }
.oc2 .why-card {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-radius: 10px;
  padding: 24px;
  display: flex;
  gap: 16px;
  align-items: flex-start;
  transition: border-color 0.2s, box-shadow 0.2s;
}
.oc2 .why-card:hover { border-color: var(--blue-mid); box-shadow: 0 4px 16px rgba(31,117,214,0.09); }
.oc2 .why-icon {
  width: 42px; height: 42px;
  border-radius: 10px;
  display: flex; align-items: center; justify-content: center;
  font-size: 20px;
  flex-shrink: 0;
}
.oc2 .wi-blue   { background: var(--blue-tint); }
.oc2 .wi-green  { background: var(--green-tint); }
.oc2 .wi-yellow { background: var(--yellow-tint); }
.oc2 .why-body h3 { font-size: 15px !important; font-weight: 700; color: var(--ink); margin-bottom: 5px !important; }
.oc2 .why-body p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

/* ── FUNDING + WHO ── */
.oc2 .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 24px; }
.oc2 .funding-card { background: var(--blue); border-radius: 12px; padding: 36px; color: #fff; }
.oc2 .funding-card h3 { font-size: 17px !important; font-weight: 700; margin-bottom: 24px !important; color: #fff !important; }
.oc2 .funding-items { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
.oc2 .fi-val { font-size: 24px; font-weight: 700; line-height: 1; }
.oc2 .fi-lbl { font-size: 11px; opacity: 0.7; margin-top: 3px; text-transform: uppercase; letter-spacing: 0.05em; }
.oc2 .who-card { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); border-radius: 12px; padding: 36px; }
.oc2 .who-card h3 { font-size: 17px !important; font-weight: 700; color: var(--ink); margin-bottom: 20px !important; }
.oc2 .who-tags { display: flex; flex-wrap: wrap; gap: 9px; }
.oc2 .who-tag {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  color: var(--grey);
  font-size: 13px;
  font-weight: 700;
  padding: 6px 13px;
  border-radius: 100px;
}

/* ── TIMELINE ── */
.oc2 .timeline { display: grid; grid-template-columns: repeat(3,1fr); position: relative; }
.oc2 .timeline::before {
  content: '';
  position: absolute;
  top: 12px; left: 12px; right: 12px;
  height: 2px;
  background: linear-gradient(90deg, var(--blue), var(--yellow), var(--green));
}
.oc2 .tl-item { position: relative; padding-top: 36px; padding-right: 20px; }
.oc2 .tl-dot {
  position: absolute; top: 5px; left: 0;
  width: 14px; height: 14px;
  border-radius: 50%;
  border: 3px solid var(--blue-tint);
  z-index: 1;
}
.oc2 .tl-item:nth-child(1) .tl-dot { background: var(--blue); }
.oc2 .tl-item:nth-child(2) .tl-dot { background: var(--yellow); }
.oc2 .tl-item:nth-child(3) .tl-dot { background: var(--green); }
.oc2 .tl-date  { font-size: 11px; font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase; margin-bottom: 5px; }
.oc2 .tl-item:nth-child(1) .tl-date { color: var(--blue); }
.oc2 .tl-item:nth-child(2) .tl-date { color: #b07f00; }
.oc2 .tl-item:nth-child(3) .tl-date { color: var(--green); }
.oc2 .tl-title { font-size: 15px; font-weight: 700; color: var(--ink); margin-bottom: 4px; }
.oc2 .tl-desc  { font-size: 13px; color: var(--grey-mid); line-height: 1.6; }

/* ── STRAND CARD ── */
.oc2 .strand-card {
  background: var(--grey-tint);
  border: 1.5px solid var(--grey-pale);
  border-left: 5px solid var(--blue);
  border-radius: 10px;
  padding: 32px 36px 28px;
  margin-bottom: 18px;
  transition: box-shadow 0.2s;
}
.oc2 .strand-card:hover { box-shadow: 0 6px 22px rgba(31,117,214,0.09); }
.oc2 .strand-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 20px;
  margin-bottom: 20px;
  flex-wrap: wrap;
}
.oc2 .strand-tag {
  display: inline-block;
  font-size: 10.5px; font-weight: 700;
  letter-spacing: 0.10em; text-transform: uppercase;
  background: var(--blue-pale); color: var(--blue);
  padding: 4px 11px; border-radius: 100px; margin-bottom: 9px;
}
.oc2 .strand-card h3 { font-size: 18px !important; font-weight: 700; color: var(--ink); margin-bottom: 5px !important; }
.oc2 .strand-card .sdesc { font-size: 13.5px; color: var(--grey-mid); line-height: 1.65; }
.oc2 .doc-grid { display: flex; flex-wrap: wrap; gap: 8px; align-items: center; }
.oc2 .doc-pill {
  display: inline-flex; align-items: center; gap: 6px;
  background: #fff; border: 1.5px solid var(--grey-pale);
  color: var(--grey) !important; padding: 7px 13px; border-radius: 6px;
  font-size: 13px; font-weight: 700;
  transition: border-color 0.15s, color 0.15s, background 0.15s;
}
.oc2 .doc-pill:hover { border-color: var(--blue); color: var(--blue) !important; background: var(--blue-tint); }
.oc2 .submit-pill {
  display: inline-flex; align-items: center; gap: 7px;
  background: var(--yellow); color: var(--ink) !important;
  padding: 10px 18px; border-radius: 6px;
  font-size: 13.5px; font-weight: 700; white-space: nowrap;
  transition: filter 0.15s, transform 0.15s;
}
.oc2 .submit-pill:hover { filter: brightness(1.07); transform: translateY(-1px); }

/* ── INFO / GLANCE ── */
.oc2 .info-inner { display: grid; grid-template-columns: 1fr 1fr; gap: 32px; align-items: start; }
.oc2 .info-left h2 { font-size: 24px !important; font-weight: 700; color: var(--ink); margin-bottom: 10px !important; }
.oc2 .info-left p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 22px; }
.oc2 .info-btns    { display: flex; gap: 10px; flex-wrap: wrap; }
.oc2 .glance { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 10px; overflow: hidden; }
.oc2 .glance-head { background: var(--blue); color: #fff; padding: 12px 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.09em; text-transform: uppercase; }
.oc2 .glance-row { display: flex; justify-content: space-between; align-items: center; padding: 11px 20px; border-bottom: 1px solid var(--grey-pale); font-size: 13.5px; }
.oc2 .glance-row:last-child { border-bottom: none; }
.oc2 .gr-key    { color: var(--grey-mid); }
.oc2 .gr-val    { font-weight: 700; color: var(--ink); }
.oc2 .gr-closed { color: var(--red) !important; }

/* ── CTA CARDS ── */
.oc2 .cta-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
.oc2 .contact-card { background: var(--blue-tint); border: 1.5px solid var(--blue-pale); border-radius: 12px; padding: 36px; }
.oc2 .contact-card h3 { font-size: 18px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .contact-card p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 22px; }
.oc2 .cta-links { display: flex; flex-direction: column; gap: 9px; }
.oc2 .cta-link {
  display: flex; align-items: center; gap: 11px;
  padding: 11px 14px; background: #fff;
  border: 1.5px solid var(--blue-pale); border-radius: 8px;
  font-size: 13.5px; font-weight: 700; color: var(--blue) !important;
  transition: border-color 0.15s, background 0.15s;
}
.oc2 .cta-link:hover { border-color: var(--blue); background: var(--blue-pale); }
.oc2 .eval-card { background: var(--yellow-tint); border: 1.5px solid var(--yellow-pale); border-radius: 12px; padding: 36px; display: flex; flex-direction: column; }
.oc2 .eval-card h3 { font-size: 18px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .eval-card p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 26px; flex: 1; }

/* ── RESPONSIVE ── */
@media (max-width: 768px) {
  .oc2 .hero { grid-template-columns: 1fr; padding: 28px; }
  .oc2 .hero-diagram { display: none; }
  .oc2 .hero-stats { grid-template-columns: 1fr; }
  .oc2 .stat { border-right: none; border-bottom: 1.5px solid var(--red-pale); }
  .oc2 .stat:last-child { border-bottom: none; }
  .oc2 .why-grid,
  .oc2 .two-col,
  .oc2 .timeline,
  .oc2 .cta-grid,
  .oc2 .info-inner { grid-template-columns: 1fr; }
  .oc2 .timeline::before { display: none; }
  .oc2 .tl-item { padding-top: 0; padding-left: 24px; padding-bottom: 20px; }
  .oc2 .tl-dot  { top: 2px; left: 0; }
  .oc2 .block   { padding: 24px; }
  .oc2 .strand-card { padding: 22px 20px; }
  .oc2 .strand-header { flex-direction: column; }
  .oc2 .funding-card, .oc2 .who-card,
  .oc2 .contact-card, .oc2 .eval-card { padding: 24px; }
  .oc2 { padding: 0 16px; }
}
</style>

<div class="oc2-escape">
<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <!-- HERO -->
  <div class="hero">
    <div>
      <div class="hero-badge"><span class="dot"></span> Open Call 1 · Status: Closed</div>
      <h1>Interconnect the <span class="accent">European</span> Digital Twin Network</h1>
      <p class="hero-sub">The LDT4SSC project, funded by the Digital Europe Programme, invited cities and organisations to apply for its first round of open calls — supporting pilots that demonstrate how existing Local Digital Twins can interconnect at European scale.</p>
      <div class="hero-btns">
        <a href="/documents/LDT4SSC_WS1_Webinar.pdf" class="btn btn-blue">↓ Download Slides</a>
        <a href="https://youtu.be/sP6zUzP-sDQ" class="btn btn-green">▶ Watch Webinar</a>
        <a href="https://youtu.be/T1SeHtgg5ew" class="btn btn-yellow">▶ Matchmaking Intro</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><div class="stat-val">€1M</div><div class="stat-lbl">Max / Consortium</div></div>
        <div class="stat"><div class="stat-val">50%</div><div class="stat-lbl">Co-funding</div></div>
        <div class="stat"><div class="stat-val">18 mo</div><div class="stat-lbl">Max Duration</div></div>
      </div>
    </div>
    <div class="hero-diagram">
      <svg viewBox="0 0 280 300" xmlns="http://www.w3.org/2000/svg">
        <circle cx="140" cy="135" r="128" fill="#FDF0EF" stroke="#F5CCCB" stroke-width="1"/>
        <circle cx="140" cy="135" r="102" fill="none" stroke="#F5CCCB" stroke-width="1" stroke-dasharray="4 7"/>
        <g stroke="#D9534F" stroke-width="1.5" opacity="0.4">
          <line x1="140" y1="135" x2="72"  y2="52"/>
          <line x1="140" y1="135" x2="208" y2="52"/>
          <line x1="140" y1="135" x2="46"  y2="170"/>
          <line x1="140" y1="135" x2="234" y2="170"/>
          <line x1="140" y1="135" x2="108" y2="232"/>
          <line x1="140" y1="135" x2="172" y2="232"/>
          <line x1="72"  y1="52"  x2="208" y2="52"  stroke="#5497DC" stroke-width="1.5" opacity="0.6"/>
          <line x1="46"  y1="170" x2="108" y2="232" stroke="#5497DC" stroke-width="1.5" opacity="0.6"/>
          <line x1="234" y1="170" x2="172" y2="232" stroke="#5497DC" stroke-width="1.5" opacity="0.6"/>
          <line x1="72"  y1="52"  x2="46"  y2="170" stroke="#5497DC" stroke-width="1" opacity="0.4"/>
          <line x1="208" y1="52"  x2="234" y2="170" stroke="#5497DC" stroke-width="1" opacity="0.4"/>
        </g>
        <circle cx="72"  cy="52"  r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="72"  y="57"  text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="208" cy="52"  r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="208" y="57"  text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="46"  cy="170" r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="46"  y="175" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="234" cy="170" r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="234" y="175" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="108" cy="232" r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="108" y="237" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="172" cy="232" r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="172" y="237" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="140" cy="135" r="30" fill="#F5CCCB"/>
        <circle cx="140" cy="135" r="20" fill="#D9534F" stroke="#fff" stroke-width="2.5"/>
        <text   x="140" y="139" text-anchor="middle" font-family="Arial" font-size="10" font-weight="700" fill="#fff">EU</text>
        <g font-family="Arial" font-size="9.5" fill="#4C5562">
          <circle cx="12" cy="278" r="5" fill="#1F75D6"/><text x="22" y="282">Connect existing DTs</text>
          <circle cx="12" cy="292" r="5" fill="#D9534F"/><text x="22" y="296">EU hub</text>
        </g>
      </svg>
    </div>
  </div>

  <!-- WHAT IS OC1 -->
  <div class="sec-label">Open Call 1</div>
  <h2 class="sec-title">Work Strand 1 — Interconnecting Existing Local Digital Twins</h2>
  <p class="sec-sub">Open Call 1 focused exclusively on Work Strand 1, supporting pilots that demonstrate how existing Local Digital Twins can be federated into a European-scale interoperable network.</p>

  <div class="block block-red" style="margin-bottom: 36px;">
    <p style="font-size:15px; color: var(--grey); line-height:1.75;">
      The Local Digital Twins for Smart and Sustainable Communities (LDT4SSC) project, funded by the Digital Europe Programme (DEP), invited applications for its first Open Call. It supported pilots demonstrating how existing Local Digital Twins can interconnect to form a European-scale network — enabling cross-border data exchange and multi-city optimisation.
    </p>
  </div>

  <div class="sec-divider"></div>

  <!-- WHY APPLY -->
  <div class="block block-grey">
    <div class="sec-label">Work Strand 1</div>
    <h2 class="sec-title">What was it for?</h2>
    <div class="why-grid">
      <div class="why-card">
        <div class="why-icon wi-blue">🌐</div>
        <div class="why-body"><h3>Federate Existing Twins</h3><p>Link your city's Local Digital Twin with others across Europe to form a federated, interoperable network enabling cross-border data exchange.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-green">📡</div>
        <div class="why-body"><h3>Enable Multi-City Optimisation</h3><p>Unlock insights and decision-making capabilities that span administrative borders — from traffic to energy flows and climate resilience.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-yellow">🧰</div>
        <div class="why-body"><h3>Use the EU LDT Toolbox</h3><p>Access open-source specifications, reference architectures and certified components that are standard-based and deployment-ready.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-blue">📈</div>
        <div class="why-body"><h3>Scale &amp; Replicate</h3><p>Build solutions designed for replication — contributing to a unified European digital ecosystem that grows with each new pilot.</p></div>
      </div>
    </div>
  </div>

  <!-- FUNDING + WHO -->
  <div class="two-col">
    <div class="funding-card">
      <h3>💰 What could you get?</h3>
      <div class="funding-items">
        <div><div class="fi-val">€1,000,000</div><div class="fi-lbl">Max per consortium</div></div>
        <div><div class="fi-val">50%</div><div class="fi-lbl">Co-funding required</div></div>
        <div><div class="fi-val">€500,000</div><div class="fi-lbl">Max per third party</div></div>
        <div><div class="fi-val">12–18 mo</div><div class="fi-lbl">Project duration</div></div>
      </div>
    </div>
    <div class="who-card">
      <h3>👥 Who could apply?</h3>
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

  <div class="sec-divider"></div>

  <!-- TIMELINE -->
  <div class="block block-blue">
    <div class="sec-label">Key Dates</div>
    <h2 class="sec-title">Call Timeline</h2>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">14 November 2025</div>
        <div class="tl-title">Open Call Launched</div>
        <div class="tl-desc">Application portal opens; all documents available for download</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">15 January 2026 · 23:59 CET</div>
        <div class="tl-title">Submission Deadline</div>
        <div class="tl-desc">All applications submitted to applications@ldt4ssc.eu</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">14 May 2026</div>
        <div class="tl-title">Pilot Start</div>
        <div class="tl-desc">Selected consortia begin their implementation phase</div>
      </div>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- HOW TO APPLY -->
  <div class="sec-label">Applications</div>
  <h2 class="sec-title">How to apply</h2>
  <p class="sec-sub">Prepare and submit all required documents for Work Strand 1 to <strong>applications@ldt4ssc.eu</strong></p>

  <div class="strand-card" style="margin-bottom:36px;">
    <div class="strand-header">
      <div>
        <span class="strand-tag">Work Strand 01</span>
        <h3>Interconnecting Existing Local Digital Twins</h3>
        <p class="sdesc">Ensure all documents are completed, signed, eligibility criteria met and alignment with Work Strand 1 objectives confirmed.</p>
      </div>
      <a href="mailto:applications@ldt4ssc.eu" class="submit-pill">✉ Submit Application</a>
    </div>
    <div class="doc-grid">
      <a href="https://ldt4ssc.eu/documents/Call_for_Pilots_Manual_WS1.pdf"        class="doc-pill">📄 Pilot Manual</a>
      <a href="https://ldt4ssc.eu/documents/ldt4ssc_application_form_ws1.docx"     class="doc-pill">📝 Application Form</a>
      <a href="https://ldt4ssc.eu/documents/letter_of_commitment.docx"              class="doc-pill">📋 Letter of Commitment</a>
      <a href="https://ldt4ssc.eu/documents/ownership_control_declaration.docx"    class="doc-pill">🔏 Ownership Declaration</a>
      <a href="https://ldt4ssc.eu/documents/financial_form.xlsx"                   class="doc-pill">💹 Financial Form</a>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- INFO SESSION -->
  <div class="block block-grey" style="margin-bottom:24px;">
    <div class="info-inner">
      <div class="info-left">
        <div class="sec-label" style="margin-bottom:8px;">Resources</div>
        <h2>Webinar Materials</h2>
        <p>Find all materials from the Open Call 1 info session, including slides, the full webinar recording and an introduction to the matchmaking platform.</p>
        <div class="info-btns" style="margin-top:22px;">
          <a href="/documents/LDT4SSC_WS1_Webinar.pdf" class="btn btn-blue">↓ Download Slides</a>
          <a href="https://youtu.be/sP6zUzP-sDQ" class="btn btn-outline">▶ Watch Recording</a>
          <a href="https://youtu.be/T1SeHtgg5ew" class="btn btn-yellow" style="margin-top:0;">▶ Matchmaking Intro</a>
        </div>
      </div>
      <div class="glance">
        <div class="glance-head">Call at a glance</div>
        <div class="glance-row"><span class="gr-key">Status</span><span class="gr-val gr-closed">● Closed</span></div>
        <div class="glance-row"><span class="gr-key">Programme</span><span class="gr-val">Digital Europe (DEP)</span></div>
        <div class="glance-row"><span class="gr-key">Work strand</span><span class="gr-val">Strand 1 only</span></div>
        <div class="glance-row"><span class="gr-key">Max per consortium</span><span class="gr-val">€1,000,000</span></div>
        <div class="glance-row"><span class="gr-key">Co-funding required</span><span class="gr-val">50%</span></div>
        <div class="glance-row"><span class="gr-key">Deadline</span><span class="gr-val">15 Jan 2026</span></div>
        <div class="glance-row"><span class="gr-key">Pilot start</span><span class="gr-val">14 May 2026</span></div>
      </div>
    </div>
  </div>

  <!-- CTA -->
  <div class="cta-grid" style="margin-bottom:8px;">
    <div class="contact-card">
      <div class="sec-label" style="margin-bottom:8px;">Get Involved</div>
      <h3>Learn more, ask questions or join a consortium</h3>
      <p>Reach out to the team, find partners via the matchmaking platform, or subscribe for updates on upcoming calls.</p>
      <div class="cta-links" style="margin-top:22px;">
        <a href="mailto:info@ldt4ssc.eu" class="cta-link">✉ Email us — info@ldt4ssc.eu</a>
        <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="cta-link">🤝 Find partners via the Matchmaking Platform</a>
        <a href="https://shorturl.at/pzMGK" class="cta-link">📬 Subscribe to the newsletter</a>
      </div>
    </div>
    <div class="eval-card">
      <div class="sec-label" style="margin-bottom:8px; color:#b07f00;">
        <span style="width:22px;height:2px;background:#b07f00;display:inline-block;border-radius:2px;flex-shrink:0;"></span>
        Evaluators
      </div>
      <h3>Apply as an Evaluator</h3>
      <p>Are you an expert in digital twins, smart cities, AI or urban planning? LDT4SSC is looking for qualified evaluators to assess open call applications. Contribute your expertise to shape Europe's digital twin ecosystem.</p>
      <a href="https://ldt4ssc.eu/call-evaluators/" class="btn btn-yellow">Learn More →</a>
    </div>
  </div>

</div>
</div>
