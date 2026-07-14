---
title: Local Digital Twins for Smart and Sustainable Communities
layout: home
description: The Local Digital Twins for Smart Communities project (LDT4SSC) supports European communities in developing, connecting and advancing Local Digital Twins for AI supported decision making
banner: /images/bannercall3.jpg
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
  text-align: center;
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

.oc2 .sec-label {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.13em;
  text-transform: uppercase;
  color: var(--blue);
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  margin-bottom: 10px;
}
.oc2 .sec-label::before,
.oc2 .sec-label::after {
  content: '';
  display: block;
  width: 22px; height: 2px;
  background: var(--blue);
  border-radius: 2px;
  flex-shrink: 0;
}
.oc2 .sec-divider { height: 1px; background: var(--grey-pale); margin: 8px 0 32px; }

.oc2 .btn { display: inline-flex; align-items: center; gap: 7px; padding: 11px 22px; border-radius: 6px; font-family: Arial, Helvetica, sans-serif; font-size: 14px; font-weight: 700; transition: filter 0.15s, transform 0.15s; cursor: pointer; line-height: 1; }
.oc2 .btn:hover { filter: brightness(1.08); transform: translateY(-1px); }
.oc2 .btn-blue   { background: var(--blue);   color: #fff !important; }
.oc2 .btn-green  { background: var(--green);  color: #fff !important; }
.oc2 .btn-yellow { background: var(--yellow); color: var(--ink) !important; }
.oc2 .btn-outline { background: #fff; border: 2px solid var(--blue); color: var(--blue) !important; }
.oc2 .btn-outline:hover { background: var(--blue-tint); filter: none; }

/* Hero */
.oc2 .hero {
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-radius: 14px;
  padding: 60px 48px;
  margin-bottom: 40px;
  text-align: center;
}
.oc2 .hero h1 {
  font-family: Arial, Helvetica, sans-serif !important;
  font-size: clamp(28px, 3.5vw, 48px) !important;
  font-weight: 700 !important;
  color: var(--ink) !important;
  line-height: 1.1 !important;
  margin-bottom: 20px !important;
  border: none !important;
  padding: 0 !important;
  max-width: 820px;
  margin-left: auto !important;
  margin-right: auto !important;
}
.oc2 .hero h1 .accent { color: var(--blue); }
.oc2 .hero-sub {
  font-size: 17px;
  color: var(--grey);
  line-height: 1.75;
  max-width: 680px;
  margin: 0 auto 36px;
}
.oc2 .hero-btns { display: flex; gap: 12px; flex-wrap: wrap; justify-content: center; margin-bottom: 44px; }
.oc2 .hero-stats { display: grid; grid-template-columns: repeat(4,1fr); border: 1.5px solid var(--blue-pale); border-radius: 10px; overflow: hidden; background: #fff; max-width: 780px; margin: 0 auto; }
.oc2 .stat { padding: 18px 20px; border-right: 1.5px solid var(--blue-pale); }
.oc2 .stat:last-child { border-right: none; }
.oc2 .stat-val { font-size: 24px; font-weight: 700; color: var(--blue); line-height: 1; }
.oc2 .stat-lbl { font-size: 11px; color: var(--grey-mid); margin-top: 4px; text-transform: uppercase; letter-spacing: 0.06em; }

/* Intro text */
.oc2 .intro-text {
  font-size: 16px;
  color: var(--grey);
  line-height: 1.85;
  max-width: 780px;
  margin: 0 auto 40px;
  text-align: center;
}

/* Goals grid */
.oc2 .goals-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 20px; margin-bottom: 40px; text-align: left; }
.oc2 .goal-card { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 12px; padding: 30px 26px; transition: box-shadow 0.2s, transform 0.2s; }
.oc2 .goal-card:hover { box-shadow: 0 8px 24px rgba(0,0,0,0.08); transform: translateY(-3px); }
.oc2 .goal-card.gc-blue   { border-top: 4px solid var(--blue); }
.oc2 .goal-card.gc-green  { border-top: 4px solid var(--green); }
.oc2 .goal-card.gc-yellow { border-top: 4px solid var(--yellow); }
.oc2 .goal-num { font-size: 36px; font-weight: 700; line-height: 1; margin-bottom: 10px; }
.oc2 .gc-blue   .goal-num { color: var(--blue-pale); }
.oc2 .gc-green  .goal-num { color: var(--green-pale); }
.oc2 .gc-yellow .goal-num { color: var(--yellow-pale); }
.oc2 .goal-card h3 { font-size: 16px !important; font-weight: 700; margin-bottom: 8px !important; }
.oc2 .gc-blue   h3 { color: var(--blue); }
.oc2 .gc-green  h3 { color: var(--green); }
.oc2 .gc-yellow h3 { color: #9a7300; }
.oc2 .goal-card p { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

/* Open calls strip */
.oc2 .calls-strip { display: grid; grid-template-columns: repeat(3,1fr); gap: 18px; margin-bottom: 40px; text-align: left; }
.oc2 .call-card { border-radius: 12px; padding: 28px 30px; display: flex; flex-direction: column; justify-content: space-between; gap: 20px; }
.oc2 .call-card-closed { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); }
.oc2 .call-card-open   { background: var(--green-tint); border: 1.5px solid var(--green-pale); }
.oc2 .call-badge { display: inline-flex; align-items: center; gap: 6px; font-size: 11px; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; padding: 4px 12px; border-radius: 100px; margin-bottom: 10px; }
.oc2 .badge-green  { background: var(--green-pale);  color: var(--green);    border: 1.5px solid var(--green); }
.oc2 .badge-closed { background: var(--grey-pale);   color: var(--grey-mid); border: 1.5px solid var(--grey-pale); }
.oc2 .badge-dot { width: 6px; height: 6px; border-radius: 50%; background: currentColor; }
.oc2 .call-card h3 { font-size: 18px !important; font-weight: 700; margin-bottom: 6px !important; color: var(--ink) !important; }
.oc2 .call-card p { font-size: 13.5px; line-height: 1.65; color: var(--grey-mid); }
.oc2 .call-meta { display: flex; flex-direction: column; gap: 5px; font-size: 12px; color: var(--grey-mid); }
.oc2 .call-meta strong { color: var(--ink); }

/* CTA row */
.oc2 .cta-row { display: flex; gap: 14px; flex-wrap: wrap; justify-content: center; margin-bottom: 8px; }

/* Hide intro image */
.intro img { display: none !important; }

@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .hero { padding: 32px 24px; }
  .oc2 .goals-grid  { grid-template-columns: 1fr; }
  .oc2 .calls-strip { grid-template-columns: 1fr; }
  .oc2 .hero-stats  { grid-template-columns: repeat(2,1fr); }
  .oc2 .hero-stats .stat:nth-child(2) { border-right: none; }
}
</style>

<div class="oc2" style="padding-top: 48px; padding-bottom: 60px;">

  <!-- Hero -->
  <div class="hero">
    <div class="sec-label">EU-Funded Project</div>
    <h1>Local Digital Twins for <span class="accent">Smart and Sustainable</span> Communities</h1>
    <p class="hero-sub">LDT4SSC supports cities, regions and public authorities across Europe in developing, connecting and advancing Local Digital Twins — enabling AI-supported decision making for a greener, more inclusive future.</p>
    <div class="hero-btns">
      <a href="/call-three/" class="btn btn-outline">View Call 3 Results</a>
      <a href="/faq/" class="btn btn-yellow">Helpdesk &amp; FAQ</a>
    </div>
    <div class="hero-stats">
      <div class="stat"><div class="stat-val">€17M</div><div class="stat-lbl">Total Funding</div></div>
      <div class="stat"><div class="stat-val">3</div><div class="stat-lbl">Open Calls</div></div>
      <div class="stat"><div class="stat-val">€1M</div><div class="stat-lbl">Max per Consortium</div></div>
      <div class="stat"><div class="stat-val">18 mo</div><div class="stat-lbl">Max Duration</div></div>
    </div>
  </div>

  <!-- Intro -->
  <div class="sec-label">About the Project</div>
  <p class="intro-text">
    LDT4SSC is building a federated, interoperable ecosystem of Local Digital Twins across Europe — virtual representations of real places that help communities understand, plan and improve their environment. Working alongside the EU's Local Digital Twin Toolbox, GAIA-X and CitiVERSE, the project brings data, infrastructure and innovation together to address today's most pressing urban challenges.
  </p>

  <div class="sec-divider"></div>

  <!-- Goals -->
  <div class="sec-label" style="margin-bottom: 18px;">What We Do</div>
  <div class="goals-grid">
    <div class="goal-card gc-blue">
      <div class="goal-num">01</div>
      <h3>Smarter Services with AI</h3>
      <p>Building advanced AI tools that respond directly to the needs of communities — from cleaner air to more efficient energy use and better resource planning.</p>
    </div>
    <div class="goal-card gc-green">
      <div class="goal-num">02</div>
      <h3>Connected Digital Twins</h3>
      <p>Linking digital twins across cities, regions and sectors to create a shared framework where data and solutions flow seamlessly across Europe.</p>
    </div>
    <div class="goal-card gc-yellow">
      <div class="goal-num">03</div>
      <h3>Sustainable Digital Futures</h3>
      <p>Promoting innovation that is ethical, fair and open — supporting Europe's vision for a greener, more inclusive Digital Decade.</p>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- Open Calls -->
  <div class="sec-label" style="margin-bottom: 18px;">Open Calls</div>
  <div class="calls-strip">

    <div class="call-card call-card-closed">
      <div>
        <div class="call-badge badge-closed"><span class="badge-dot"></span> Closed</div>
        <h3>Open Call 1</h3>
        <p>Work Strand 1 — interconnecting existing Local Digital Twins. Now closed; selected consortia are in the implementation phase.</p>
      </div>
      <div>
        <div class="call-meta" style="margin-bottom: 16px;">
          <span>Status: <strong>Closed</strong></span>
        </div>
        <a href="https://ldt4ssc.eu/call-one/" class="btn btn-outline" style="font-size:13px; padding: 9px 16px;">View Call 1</a>
      </div>
    </div>

    <div class="call-card call-card-closed">
      <div>
        <div class="call-badge badge-closed"><span class="badge-dot"></span> Closed</div>
        <h3>Open Call 2</h3>
        <p>Work Strands 1, 2 and 3 — interconnecting existing Local Digital Twins, creating new ones, and adding advanced AI capabilities to the EU LDT Toolbox.</p>
      </div>
      <div>
        <div class="call-meta" style="margin-bottom: 16px;">
          <span>Status: <strong>Closed</strong></span>
        </div>
        <a href="/call-two/" class="btn btn-outline" style="font-size:13px; padding: 9px 16px;">View Call 2</a>
      </div>
    </div>

    <div class="call-card call-card-closed">
      <div>
        <div class="call-badge badge-closed"><span class="badge-dot"></span> Closed</div>
        <h3>Open Call 3</h3>
        <p>Work Strands 1, 2 and 3 — interconnecting existing Local Digital Twins, creating new ones, and adding advanced AI services to the EU LDT Toolbox. Now closed; selected consortia to be announced.</p>
      </div>
      <div>
        <div class="call-meta" style="margin-bottom: 16px;">
          <span>Status: <strong>Closed</strong></span>
          <span>Deadline: <strong>13 July 2026</strong></span>
        </div>
        <a href="/call-three/" class="btn btn-outline" style="font-size:13px; padding: 9px 16px;">View Call 3</a>
      </div>
    </div>

  </div>

  <div class="sec-divider"></div>

  <!-- CTA -->
  <div class="sec-label" style="margin-bottom: 16px;">Get Involved</div>
  <p style="font-size: 15px; color: var(--grey-mid); max-width: 560px; margin: 0 auto 28px; line-height: 1.7;">Find consortium partners, subscribe for updates or join the stakeholder community shaping Europe's digital twin ecosystem.</p>
  <div class="cta-row">
    <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="btn btn-blue">Find Partners via Matchmaking Platform</a>
    <a href="https://shorturl.at/pzMGK" class="btn btn-yellow">Subscribe to Newsletter</a>
    <a href="https://forms.gle/v17Y7df5DUwpCRZP6" class="btn btn-green">Join the Stakeholder Forum</a>
  </div>

</div>
