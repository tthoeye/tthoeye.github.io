---
layout: fullwidth
description: The Local Digital Twins for Smart Communities project (LDT4SSC) supports European communities in developing, connecting and advancing Local Digital Twins for AI supported decision making
---

<style>
/* ── Break out of col-md-8 and stretch full row width ── */
.oc2-escape {
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  width: 100vw;
  /* CRITICAL: do NOT set z-index here — lets the nav dropdown sit above */
}

/* ── All styles scoped to .oc2 ── */
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

/* CSS variables */
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
  margin: 8px 0 32px;
}

/* ── PAGE HERO ── */
.oc2 .page-hero {
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-radius: 14px;
  padding: 48px;
  margin-bottom: 40px;
  text-align: center;
}
.oc2 .page-hero h1 {
  font-family: Arial, Helvetica, sans-serif !important;
  font-size: clamp(28px, 3.5vw, 48px) !important;
  font-weight: 700 !important;
  color: var(--ink) !important;
  line-height: 1.1 !important;
  margin-bottom: 16px !important;
  border: none !important;
  padding: 0 !important;
}
.oc2 .page-hero h1 .accent { color: var(--blue); }
.oc2 .page-hero-sub {
  font-size: 16px;
  color: var(--grey);
  line-height: 1.7;
  max-width: 680px;
  margin: 0 auto 28px;
}
.oc2 .hero-stats {
  display: inline-grid;
  grid-template-columns: repeat(3, 1fr);
  border: 1.5px solid var(--blue-pale);
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
  margin-top: 8px;
}
.oc2 .stat { padding: 16px 28px; border-right: 1.5px solid var(--blue-pale); }
.oc2 .stat:last-child { border-right: none; }
.oc2 .stat-val { font-size: 24px; font-weight: 700; color: var(--blue); line-height: 1; }
.oc2 .stat-lbl { font-size: 11px; color: var(--grey-mid); margin-top: 3px; text-transform: uppercase; letter-spacing: 0.06em; }

/* ── INTRO TEXT ── */
.oc2 .intro-block {
  font-size: 16px;
  line-height: 1.75;
  color: var(--grey);
  margin-bottom: 40px;
}
.oc2 .intro-block p { margin-bottom: 14px; }
.oc2 .intro-block p:last-child { margin-bottom: 0; }
.oc2 .hl-blue   { color: var(--blue); font-weight: 700; }
.oc2 .hl-green  { color: var(--green); font-weight: 700; }

/* ── CALL CARDS ── */
.oc2 .call-card {
  background: var(--grey-tint);
  border: 1.5px solid var(--grey-pale);
  border-left: 5px solid var(--blue);
  border-radius: 10px;
  padding: 32px 36px 28px;
  margin-bottom: 18px;
  transition: box-shadow 0.2s;
}
.oc2 .call-card:hover { box-shadow: 0 6px 22px rgba(31,117,214,0.09); }
.oc2 .call-card-head {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
  margin-bottom: 14px;
}
.oc2 .call-tag {
  display: inline-block;
  font-size: 10.5px; font-weight: 700;
  letter-spacing: 0.10em; text-transform: uppercase;
  background: var(--blue-pale); color: var(--blue);
  padding: 4px 11px; border-radius: 100px; margin-bottom: 9px;
}
.oc2 .call-tag-green {
  background: var(--green-pale); color: var(--green);
}
.oc2 .call-tag-yellow {
  background: var(--yellow-pale); color: #9a7300;
}
.oc2 .call-card h3 {
  font-size: 20px !important;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 6px !important;
}
.oc2 .call-meta {
  font-size: 13.5px;
  color: var(--grey-mid);
  margin-bottom: 4px;
}
.oc2 .call-meta strong { color: var(--ink); }
.oc2 .call-strands {
  font-size: 13.5px;
  color: var(--grey-mid);
  line-height: 1.8;
  margin-top: 10px;
  padding-left: 2px;
}
.oc2 .call-strands li { list-style: none; padding-left: 0; }
.oc2 .call-strands li::before { content: '• '; color: var(--blue); font-weight: 700; }

.oc2 .call-link {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  background: var(--blue);
  color: #fff !important;
  font-size: 13.5px;
  font-weight: 700;
  padding: 10px 18px;
  border-radius: 6px;
  white-space: nowrap;
  transition: filter 0.15s, transform 0.15s;
  flex-shrink: 0;
  align-self: flex-start;
  margin-top: 4px;
}
.oc2 .call-link:hover { filter: brightness(1.1); transform: translateY(-1px); }

.oc2 .call-coming {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  background: var(--grey-tint);
  color: var(--grey-mid) !important;
  font-size: 13.5px;
  font-weight: 700;
  padding: 10px 18px;
  border-radius: 6px;
  border: 1.5px solid var(--grey-pale);
  white-space: nowrap;
  flex-shrink: 0;
  align-self: flex-start;
  margin-top: 4px;
}

/* OC1 / OC2 / OC3 accent colours */
.oc2 .card-oc1 { border-left-color: var(--blue); }
.oc2 .card-oc2 { border-left-color: var(--green); }
.oc2 .card-oc3 { border-left-color: var(--yellow); }

/* ── BUDGET CARDS ── */
.oc2 .budget-row {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  margin-bottom: 40px;
}
.oc2 .budget-card {
  flex: 1;
  min-width: 220px;
  border-radius: 12px;
  padding: 24px;
}
.oc2 .bc-green  { background: rgba(41,163,41,0.10);  border: 1.5px solid var(--green-pale); }
.oc2 .bc-blue   { background: rgba(31,117,214,0.08); border: 1.5px solid var(--blue-pale); }
.oc2 .bc-yellow { background: rgba(245,180,0,0.18);  border: 1.5px solid var(--yellow-pale); }
.oc2 .budget-card strong { display: block; font-size: 15px; margin-bottom: 4px; }
.oc2 .bc-green  strong { color: var(--green); }
.oc2 .bc-blue   strong { color: var(--blue); }
.oc2 .bc-yellow strong { color: #9a7300; }
.oc2 .budget-card span { font-size: 14px; color: var(--grey-mid); }

/* ── RESPONSIVE ── */
@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .page-hero { padding: 28px 20px; }
  .oc2 .hero-stats { grid-template-columns: 1fr; display: grid; }
  .oc2 .stat { border-right: none; border-bottom: 1.5px solid var(--blue-pale); }
  .oc2 .stat:last-child { border-bottom: none; }
  .oc2 .call-card { padding: 22px 18px; }
  .oc2 .call-card-head { flex-direction: column; }
}
</style>

<div class="oc2-escape">
<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <!-- HERO -->
  <div class="page-hero">
    <div class="sec-label" style="justify-content:center;">LDT4SSC Project</div>
    <h1>Open <span class="accent">Calls</span></h1>
    <p class="page-hero-sub">
      LDT4SSC is launching three rounds of open calls to fund and support pilot projects across Europe —
      focusing on resource management, climate resilience and energy efficiency.
    </p>
    <div class="hero-stats">
      <div class="stat"><div class="stat-val">15–20</div><div class="stat-lbl">Pilot projects</div></div>
      <div class="stat"><div class="stat-val">€17M</div><div class="stat-lbl">Total funding</div></div>
      <div class="stat"><div class="stat-val">3</div><div class="stat-lbl">Open call rounds</div></div>
    </div>
  </div>

  <!-- INTRO -->
  <div class="sec-label">About the Open Calls</div>
  <div class="intro-block">
    <p>
      To bring ideas to life, <span class="hl-blue">LDT4SSC</span> is launching three rounds of open calls
      to fund and support <span class="hl-green">15–20 pilot projects across Europe</span>.
    </p>
    <p>
      These pilots will focus on critical areas such as
      <span class="hl-green">resource management</span>,
      <span class="hl-green">climate resilience</span> and
      <span class="hl-green">energy efficiency</span>,
      developing AI-driven services tailored to local needs.
    </p>
    <p>
      By connecting solutions across sectors and borders, the pilots will help create
      a <span class="hl-blue">unified digital ecosystem</span> that can be scaled and replicated across Europe.
    </p>
  </div>

  <div class="sec-divider"></div>

  <!-- OPEN CALL SCHEDULE -->
  <div class="sec-label">Schedule</div>
  <h2 class="sec-title">Open Call Schedule</h2>
  <p class="sec-sub">Three rounds of funding across all work strands — from interconnecting existing twins to deploying advanced AI capabilities.</p>

  <!-- OC1 -->
  <div class="call-card card-oc1">
    <div class="call-card-head">
      <div>
        <span class="call-tag">Open Call 1</span>
        <h3>Interconnecting Existing Local Digital Twins</h3>
        <div class="call-meta"><strong>Work Strand:</strong> Inter-connection of existing Local Digital Twins</div>
        <div class="call-meta" style="margin-top:6px;"><strong>Launch date:</strong> 14 November 2025</div>
      </div>
      <a href="https://ldt4ssc.eu/call-one/" class="call-link">View Open Call 1 →</a>
    </div>
  </div>

  <!-- OC2 -->
  <div class="call-card card-oc2" style="border-left-color: var(--green);">
    <div class="call-card-head">
      <div>
        <span class="call-tag call-tag-green">Open Call 2</span>
        <h3>All Three Work Strands Open</h3>
        <div class="call-meta"><strong>Work Strands:</strong></div>
        <ul class="call-strands">
          <li>Work Strand 1 – Inter-connection of existing LDTs</li>
          <li>Work Strand 2 – Creation of LDTs based on common needs</li>
          <li>Work Strand 3 – Adding new and advanced AI services to the EU LDT Toolbox</li>
        </ul>
        <div class="call-meta" style="margin-top:12px;"><strong>Launch date:</strong> 2 February 2026</div>
      </div>
      <a href="https://ldt4ssc.eu/call-two/" class="call-link" style="background: var(--green);">View Open Call 2 →</a>
    </div>
  </div>

  <!-- OC3 -->
  <div class="call-card card-oc3" style="border-left-color: var(--yellow); margin-bottom: 36px;">
    <div class="call-card-head">
      <div>
        <span class="call-tag call-tag-yellow">Open Call 3</span>
        <h3>Interconnecting, Creating &amp; Enhancing Local Digital Twins</h3>
        <div class="call-meta"><strong>Work Strands:</strong></div>
        <ul class="call-strands">
          <li>Work Strand 1 – Inter-connection of existing Local Digital Twins</li>
          <li>Work Strand 2 – Creation of LDTs based on common needs</li>
          <li>Work Strand 3 – Adding new and advanced AI services to the EU LDT Toolbox</li>
        </ul>
        <div class="call-meta" style="margin-top:12px;"><strong>Launch date:</strong> 13 May 2026</div>
      </div>
      <a href="https://ldt4ssc.eu/call-three/" class="call-link" style="background: #9a7300;">More information →</a>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- TIMELINE & BUDGET -->
  <div class="sec-label">Timeline &amp; Budget</div>
  <h2 class="sec-title">Funding Overview</h2>
  <p class="sec-sub">Each pilot receives substantial funding and a dedicated implementation period to design, build and deploy their Local Digital Twin solution.</p>

  <div class="budget-row">
    <div class="budget-card bc-green">
      <strong>Number of pilots</strong>
      <span>15–20 across all rounds</span>
    </div>
    <div class="budget-card bc-blue">
      <strong>Pilot duration</strong>
      <span>Approximately 18 months</span>
    </div>
    <div class="budget-card bc-yellow">
      <strong>Funding per pilot</strong>
      <span>Around €1 million</span>
    </div>
  </div>

</div>
</div>
