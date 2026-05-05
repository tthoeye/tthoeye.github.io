---
title: About
layout: fullwidth
description: About the Project
intro_image: "images/illustrations/reading.jpg"
intro_image_absolute: false
intro_image_hide_on_mobile: true
bodyClass: page-about
---

<style>

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
  margin: 8px 0 36px;
}

/* ── HERO ── */
.oc2 .hero {
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-radius: 14px;
  padding: 52px 48px;
  margin-bottom: 40px;
  display: grid;
  grid-template-columns: 1fr 280px;
  gap: 48px;
  align-items: center;
}
.oc2 .hero-badge {
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
  padding: 5px 12px;
  border-radius: 100px;
  margin-bottom: 18px;
}
.oc2 .hero-badge .dot { width:7px; height:7px; background:var(--green); border-radius:50%; }
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
  line-height: 1.75;
  margin-bottom: 28px;
}
.oc2 .hero-stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  border: 1.5px solid var(--blue-pale);
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
}
.oc2 .stat { padding: 16px 18px; border-right: 1.5px solid var(--blue-pale); }
.oc2 .stat:last-child { border-right: none; }
.oc2 .stat-val { font-size: 22px; font-weight: 700; color: var(--blue); line-height: 1; }
.oc2 .stat-lbl { font-size: 11px; color: var(--grey-mid); margin-top: 3px; text-transform: uppercase; letter-spacing: 0.06em; }
.oc2 .hero-diagram svg { width: 100%; height: auto; display: block; }

/* ── BLOCKS ── */
.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey   { background: var(--grey-tint);   border: 1.5px solid var(--grey-pale); }
.oc2 .block-blue   { background: var(--blue-tint);   border: 1.5px solid var(--blue-pale); }
.oc2 .block-green  { background: var(--green-tint);  border: 1.5px solid var(--green-pale); }
.oc2 .block-yellow { background: var(--yellow-tint); border: 1.5px solid var(--yellow-pale); }

/* ── WORK PILLARS ── */
.oc2 .pillars-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-bottom: 36px;
}
.oc2 .pillar {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-top: 4px solid var(--blue);
  border-radius: 10px;
  padding: 28px 24px;
  transition: box-shadow 0.2s;
}
.oc2 .pillar:hover { box-shadow: 0 6px 20px rgba(31,117,214,0.10); }
.oc2 .pillar-icon { font-size: 28px; margin-bottom: 14px; }
.oc2 .pillar h3 { font-size: 16px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .pillar p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }
.oc2 .pillar-green  { border-top-color: var(--green); }
.oc2 .pillar-yellow { border-top-color: var(--yellow); }

/* ── IMPACT LIST ── */
.oc2 .impact-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 14px;
}
.oc2 .impact-item {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-radius: 10px;
  padding: 20px 22px;
  display: flex;
  gap: 14px;
  align-items: flex-start;
  transition: border-color 0.2s, box-shadow 0.2s;
}
.oc2 .impact-item:hover { border-color: var(--blue-mid); box-shadow: 0 4px 14px rgba(31,117,214,0.08); }
.oc2 .impact-icon {
  width: 36px; height: 36px;
  border-radius: 8px;
  background: var(--blue-tint);
  display: flex; align-items: center; justify-content: center;
  font-size: 17px;
  flex-shrink: 0;
}
.oc2 .impact-body p { font-size: 13.5px; color: var(--grey-mid); line-height: 1.65; font-weight: 600; color: var(--ink); }

/* ── FUNDING BAND ── */
.oc2 .funding-band {
  background: var(--blue);
  border-radius: 12px;
  padding: 32px 40px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  flex-wrap: wrap;
  margin-bottom: 36px;
}
.oc2 .funding-band-text h3 { font-size: 18px !important; font-weight: 700; color: #fff !important; margin-bottom: 4px !important; }
.oc2 .funding-band-text p  { font-size: 13.5px; color: rgba(255,255,255,0.75); line-height: 1.6; }
.oc2 .funding-band-stats { display: flex; gap: 32px; }
.oc2 .fb-stat .fi-val { font-size: 26px; font-weight: 700; color: #fff; line-height: 1; }
.oc2 .fb-stat .fi-lbl { font-size: 11px; color: rgba(255,255,255,0.65); text-transform: uppercase; letter-spacing: 0.05em; margin-top: 3px; }

/* ── PARTNERS ── */
.oc2 .partners-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2px;
  background: var(--grey-pale);
  border: 1.5px solid var(--grey-pale);
  border-radius: 12px;
  overflow: hidden;
  margin-bottom: 24px;
}
.oc2 .partner-cell {
  background: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 28px 20px;
  transition: background 0.2s;
}
.oc2 .partner-cell:hover { background: var(--blue-tint); }
.oc2 .partner-cell img {
  max-height: 48px;
  max-width: 120px;
  width: auto;
  object-fit: contain;
  filter: grayscale(30%);
  transition: filter 0.2s;
}
.oc2 .partner-cell:hover img { filter: none; }

/* ── TIMELINE ── */
.oc2 .timeline { display: grid; grid-template-columns: repeat(3, 1fr); position: relative; }
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

.oc2 .btn {
  display: inline-flex; align-items: center; gap: 7px;
  padding: 11px 20px; border-radius: 6px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 14px; font-weight: 700;
  transition: filter 0.15s, transform 0.15s;
  cursor: pointer; line-height: 1;
}
.oc2 .btn:hover { filter: brightness(1.08); transform: translateY(-1px); }
.oc2 .btn-blue   { background: var(--blue);   color: #fff !important; }
.oc2 .btn-yellow { background: var(--yellow); color: var(--ink) !important; }
.oc2 .btn-outline { background: #fff; border: 2px solid var(--blue); color: var(--blue) !important; }
.oc2 .btn-outline:hover { background: var(--blue-tint); filter: none; }

/* ── RESPONSIVE ── */
@media (max-width: 900px) {
  .oc2 .pillars-grid { grid-template-columns: 1fr; }
  .oc2 .partners-grid { grid-template-columns: repeat(2, 1fr); }
}
@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .hero { grid-template-columns: 1fr; padding: 28px; }
  .oc2 .hero-diagram { display: none; }
  .oc2 .hero-stats { grid-template-columns: 1fr; }
  .oc2 .stat { border-right: none; border-bottom: 1.5px solid var(--blue-pale); }
  .oc2 .stat:last-child { border-bottom: none; }
  .oc2 .impact-grid,
  .oc2 .timeline,
  .oc2 .cta-grid { grid-template-columns: 1fr; }
  .oc2 .timeline::before { display: none; }
  .oc2 .tl-item { padding-top: 0; padding-left: 24px; padding-bottom: 20px; }
  .oc2 .tl-dot  { top: 2px; left: 0; }
  .oc2 .block   { padding: 24px; }
  .oc2 .funding-band { flex-direction: column; padding: 24px; }
  .oc2 .funding-band-stats { flex-wrap: wrap; gap: 20px; }
  .oc2 .partners-grid { grid-template-columns: repeat(2, 1fr); }
  .oc2 .contact-card, .oc2 .eval-card { padding: 24px; }
}
</style>

<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <!-- HERO -->
  <div class="hero">
    <div>
      <div class="hero-badge"><span class="dot"></span> EU-funded · Digital Europe Programme</div>
      <h1>Local Digital Twins for <span class="accent">Smart</span> Communities</h1>
      <p class="hero-sub">LDT4SSC — short for Local Digital Twins for Smart Sustainable Cities — helps cities meet these challenges by sharing powerful digital tools called Local Digital Twins. Think of them as digital copies of real places. They use data and Artificial Intelligence (AI) to help local governments make smarter, faster decisions — for example, predicting traffic, planning green spaces or improving waste collection.</p>
      <div class="hero-stats">
        <div class="stat"><div class="stat-val">10</div><div class="stat-lbl">Partner organisations</div></div>
        <div class="stat"><div class="stat-val">2025–28</div><div class="stat-lbl">Project period</div></div>
        <div class="stat"><div class="stat-val">€17M</div><div class="stat-lbl">Total funding</div></div>
      </div>
    </div>
    <div class="hero-diagram">
      <svg viewBox="0 0 280 300" xmlns="http://www.w3.org/2000/svg">
        <circle cx="140" cy="140" r="128" fill="#EBF4FD" stroke="#C8DFF5" stroke-width="1"/>
        <circle cx="140" cy="140" r="100" fill="none" stroke="#C8DFF5" stroke-width="1" stroke-dasharray="4 7"/>
        <g stroke="#5497DC" stroke-width="1.2" opacity="0.45">
          <line x1="140" y1="140" x2="72"  y2="57"/>
          <line x1="140" y1="140" x2="208" y2="57"/>
          <line x1="140" y1="140" x2="46"  y2="175"/>
          <line x1="140" y1="140" x2="234" y2="175"/>
          <line x1="140" y1="140" x2="108" y2="237"/>
          <line x1="140" y1="140" x2="172" y2="237"/>
        </g>
        <!-- city nodes -->
        <circle cx="72"  cy="57"  r="16" fill="#EDF7E8" stroke="#29A329" stroke-width="2"/>
        <text   x="72"  y="61"  text-anchor="middle" font-family="Arial" font-size="8" font-weight="700" fill="#29A329">🏙</text>
        <circle cx="208" cy="57"  r="16" fill="#EDF7E8" stroke="#29A329" stroke-width="2"/>
        <text   x="208" y="61"  text-anchor="middle" font-family="Arial" font-size="8" font-weight="700" fill="#29A329">🏙</text>
        <circle cx="46"  cy="175" r="16" fill="#FFFAE8" stroke="#F5B400" stroke-width="2"/>
        <text   x="46"  y="179" text-anchor="middle" font-family="Arial" font-size="8" font-weight="700" fill="#b07f00">🤖</text>
        <circle cx="234" cy="175" r="16" fill="#FFFAE8" stroke="#F5B400" stroke-width="2"/>
        <text   x="234" y="179" text-anchor="middle" font-family="Arial" font-size="8" font-weight="700" fill="#b07f00">🤖</text>
        <circle cx="108" cy="237" r="16" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="108" y="241" text-anchor="middle" font-family="Arial" font-size="8" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="172" cy="237" r="16" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/>
        <text   x="172" y="241" text-anchor="middle" font-family="Arial" font-size="8" font-weight="700" fill="#1F75D6">DT</text>
        <!-- centre -->
        <circle cx="140" cy="140" r="30" fill="#C8DFF5"/>
        <circle cx="140" cy="140" r="20" fill="#1F75D6" stroke="#fff" stroke-width="2.5"/>
        <text   x="140" y="144" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#fff">EU</text>
        <!-- legend -->
        <g font-family="Arial" font-size="9" fill="#4C5562">
          <circle cx="12" cy="272" r="5" fill="#29A329"/><text x="22" y="276">Cities</text>
          <circle cx="12" cy="286" r="5" fill="#F5B400"/><text x="22" y="290">AI services</text>
          <circle cx="90" cy="272" r="5" fill="#1F75D6"/><text x="100" y="276">Digital Twins</text>
        </g>
      </svg>
    </div>
  </div>

  <!-- OUR WORK -->
  <div class="sec-label">Our Work</div>
  <h2 class="sec-title">Our Work</h2>
  <p class="sec-sub">Across Europe, cities and communities face similar challenges: how to use energy more efficiently, reduce pollution, improve public services and adapt to climate change.</p>

  <div class="pillars-grid">
    <div class="pillar">
      <div class="pillar-icon">🌐</div>
      <h3>Linking digital twins across Europe</h3>
      <p>We connect the tools cities already use — like traffic monitors, energy trackers or environmental sensors — into a shared European network. This makes it easier to collaborate, reuse solutions and give smaller communities access to cutting-edge technology.</p>
    </div>
    <div class="pillar pillar-green">
      <div class="pillar-icon">🏙</div>
      <h3>Testing smart solutions in the real world</h3>
      <p>Through pilot projects, we support local teams to develop and test AI-driven services. These real-life pilots improve everyday life by making public services faster, decision-making smarter and cities more sustainable.</p>
    </div>
    <div class="pillar pillar-yellow">
      <div class="pillar-icon">🤖</div>
      <h3>Expanding Europe's toolbox with AI innovation</h3>
      <p>We are enriching the EU's Local Digital Twin Toolbox with new AI-powered tools — from prediction models to self-organising systems — so cities can respond to challenges more quickly and effectively.</p>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- IMPACT -->
  <div class="block block-grey">
    <div class="sec-label">Impact for Europe</div>
    <h2 class="sec-title">Impact for Europe</h2>
    <p class="sec-sub" style="margin-bottom:24px;">Europe's digital transformation is often slowed down by high costs, complex rules and scattered expertise. LDT4SSC helps break down these barriers by:</p>
    <div class="impact-grid">
      <div class="impact-item">
        <div class="impact-icon">🤝</div>
        <div class="impact-body"><p>Bringing cities together to share solutions</p></div>
      </div>
      <div class="impact-item">
        <div class="impact-icon">⚖️</div>
        <div class="impact-body"><p>Supporting open, ethical, people-centred technology</p></div>
      </div>
      <div class="impact-item">
        <div class="impact-icon">📐</div>
        <div class="impact-body"><p>Creating fair digital markets with open standards</p></div>
      </div>
      <div class="impact-item">
        <div class="impact-icon">🇪🇺</div>
        <div class="impact-body"><p>Working with the European Digital Infrastructure Consortium (EDIC) to build strong, connected systems across borders</p></div>
      </div>
    </div>
  </div>

  <!-- FUNDING BAND -->
  <div class="funding-band">
    <div class="funding-band-text">
      <h3>Funded by the Digital Europe Programme</h3>
      <p>This project directly supports the EU's vision of a digital, green and inclusive society.</p>
    </div>
    <div class="funding-band-stats">
      <div class="fb-stat"><div class="fi-val">June 2025</div><div class="fi-lbl">Project start</div></div>
      <div class="fb-stat"><div class="fi-val">Dec 2028</div><div class="fi-lbl">Project end</div></div>
      <div class="fb-stat"><div class="fi-val">15–20</div><div class="fi-lbl">Pilot projects</div></div>
    </div>
  </div>

  <!-- PROJECT TIMELINE -->
  <div class="block block-blue" style="margin-bottom:36px;">
    <div class="sec-label">Project Timeline</div>
    <h2 class="sec-title">Key Milestones</h2>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">June 2025</div>
        <div class="tl-title">Project Launch</div>
        <div class="tl-desc">The project officially started in June 2025</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">November 2025 – May 2026</div>
        <div class="tl-title">Three Open Calls</div>
        <div class="tl-desc">Multi-stakeholder consortia invited to propose impactful, real-world use cases</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">December 2028</div>
        <div class="tl-title">Project Completion</div>
        <div class="tl-desc">The project will run until December 2028</div>
      </div>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- PARTNERS -->
  <div class="sec-label">Our Partners</div>
  <h2 class="sec-title">Our Partners</h2>
  <p class="sec-sub">LDT4SSC brings together a diverse and experienced group of partners from across Europe. The consortium includes public research institutes, universities, non-profits, local authorities and open-source technology providers, all working together to advance interoperable Local Digital Twins and AI-driven services across Europe. This collaboration is made possible with the support of the European Union as the funding authority, ensuring alignment with broader EU digital and innovation priorities.</p>

  <div class="partners-grid">
    <a href="https://oascities.org"          class="partner-cell"><img src="../images/partners/oasc.png"           alt="OASC"></a>
    <a href="https://www.list.lu"            class="partner-cell"><img src="../images/partners/list.png"           alt="LIST"></a>
    <a href="https://www.kereval.com"        class="partner-cell"><img src="../images/partners/kereval.png"        alt="Kereval"></a>
    <a href="https://taltech.ee"             class="partner-cell"><img src="../images/partners/taltech.png"        alt="TalTech"></a>
    <a href="https://enoll.org"              class="partner-cell"><img src="../images/partners/enoll.svg"          alt="ENoLL"></a>
    <a href="https://www.cerema.fr"          class="partner-cell"><img src="../images/partners/newceremalogo.png"  alt="Cerema"></a>
    <a href="https://technopolis-group.com/" class="partner-cell"><img src="../images/partners/technopolis.png"    alt="Technopolis"></a>
    <a href="https://www.libelium.com/"      class="partner-cell"><img src="../images/partners/libellium.jpg"      alt="Libelium"></a>
    <a href="https://www.ugent.be"           class="partner-cell"><img src="../images/partners/ugent.png"          alt="UGent"></a>
  </div>

  <div class="sec-divider"></div>

  <!-- CTA -->
  <div class="cta-grid" style="margin-bottom:8px;">
    <div class="contact-card">
      <div class="sec-label" style="margin-bottom:8px;">Get Involved</div>
      <h3>Learn more, ask questions or join a consortium</h3>
      <p>Reach out to the team, find partners via the matchmaking platform, or subscribe for updates on upcoming open calls.</p>
      <div class="cta-links" style="margin-top:22px;">
        <a href="https://ldt4ssc.eu/faq/" class="cta-link">❓ Visit our Helpdesk &amp; FAQ</a>
        <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="cta-link">🤝 Find partners via the Matchmaking Platform</a>
        <a href="https://shorturl.at/pzMGK" class="cta-link">📬 Subscribe to the newsletter</a>
      </div>
    </div>
    <div class="eval-card">
      <div class="sec-label" style="margin-bottom:8px; color:#b07f00;">
        <span style="width:22px;height:2px;background:#b07f00;display:inline-block;border-radius:2px;flex-shrink:0;"></span>
        Open Calls
      </div>
      <h3>Apply for Funding</h3>
      <p>LDT4SSC is running three rounds of open calls, offering up to €1 million per consortium to fund real-world Local Digital Twin pilot projects across Europe.</p>
      <a href="/open-calls/" class="btn btn-yellow">View Open Calls →</a>
    </div>
  </div>

</div>
