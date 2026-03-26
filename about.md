---
title: About
layout: fullwidth
description: About the Project
---

<style>
/* ── Break out of container ── */
.oc2-escape {
  position: relative;
  left: 50%;
  margin-left: -50vw;
  width: 100vw;
}

/* ── Page styling ── */
.oc2 {
  font-family: Arial, Helvetica, sans-serif;
  color: #4C5562;
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 32px;
  overflow: visible; /* allow dropdowns to show */
}

/* palette */
.oc2 {
  --blue: #1F75D6;
  --green: #29A329;
  --yellow: #F5B400;
  --grey: #4C5562;
  --grey-mid: #7A8494;
  --grey-pale: #D8DCE3;
  --grey-tint: #F2F3F5;
  --blue-tint: rgba(31,117,214,0.1);
  --green-tint: rgba(41,163,41,0.1);
  --yellow-tint: rgba(245,180,0,0.1);
}

/* HERO */
.hero {
  background: linear-gradient(135deg, var(--blue-tint), #ffffff);
  border-radius: 14px;
  padding: 52px;
  margin-bottom: 48px;
  position: relative;
  z-index: 1;
}
.hero h1 {
  font-size: clamp(28px,3vw,44px);
  font-weight: 700;
}
.hero .accent { color: var(--blue); }
.hero p {
  margin-top: 12px;
  font-size: 16px;
  line-height: 1.7;
}

/* SECTION TITLES */
.sec-label {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: .12em;
  color: var(--blue);
  margin-bottom: 8px;
}
.sec-title {
  font-size: clamp(22px,2.5vw,32px);
  font-weight: 700;
  margin-bottom: 10px;
}
.sec-sub {
  color: var(--grey-mid);
  margin-bottom: 28px;
  line-height: 1.7;
}

/* GRID CARDS */
.grid {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  gap: 20px;
  margin-bottom: 40px;
}
.card {
  background:#ffffff;
  border-radius:14px;
  padding:28px;
  transition:.2s;
  box-shadow: 0 2px 6px rgba(0,0,0,0.03);
}
.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
}
.icon {
  font-size: 28px;
  margin-bottom: 12px;
}
.card h3 {
  font-size:17px;
  margin-bottom:8px;
  font-weight: 700;
}
.card p {
  font-size:14px;
  color: var(--grey-mid);
  line-height:1.7;
}

/* IMPACT BLOCK */
.block {
  border-radius:14px;
  padding:36px;
  margin-bottom:50px; /* extra space below */
}
.block-grey {
  background: var(--grey-tint);
  border:1px solid var(--grey-pale);
}

/* PARTNERS */
.partners {
  display:grid;
  grid-template-columns: repeat(5,1fr);
  gap: 22px;
  margin-bottom:50px; /* extra space below */
}
.partner {
  display:flex;
  align-items:center;
  justify-content:center;
  padding:16px;
  border-radius:10px;
  background:#fff;
  border:1px solid var(--grey-pale);
  transition:.2s;
}
.partner:hover {
  border-color: var(--blue);
  box-shadow: 0 6px 18px rgba(31,117,214,0.08);
}
.partner img {
  max-width:100%;
  max-height:42px;
  filter: none; /* keep original colors */
  opacity:1;
}

/* responsive */
@media(max-width:900px){
  .grid { grid-template-columns:1fr; }
  .partners { grid-template-columns: repeat(2,1fr); }
  .hero { padding:28px; }
}

/* ── DROP-DOWN FIX ── */
.navbar, .dropdown-menu {
  position: relative;
  z-index: 9999 !important; /* always above hero/content */
}
</style>

<div class="oc2-escape">
<div class="oc2">

  <!-- HERO -->
  <div class="hero">
    <div class="sec-label">About</div>
    <h1>Our <span class="accent">Work</span></h1>
    <p>Across Europe, cities and communities face similar challenges: how to use energy more efficiently, reduce pollution, improve public services and adapt to climate change.</p>
    <p>LDT4SSC — short for Local Digital Twins for Smart Sustainable Cities — helps cities meet these challenges by sharing powerful digital tools called Local Digital Twins. Think of them as digital copies of real places. They use data and Artificial Intelligence (AI) to help local governments make smarter, faster decisions — for example, predicting traffic, planning green spaces or improving waste collection.</p>
  </div>

  <!-- OUR WORK CARDS -->
  <div class="grid">
    <div class="card">
      <div class="icon">🔗</div>
      <h3>Linking digital twins across Europe</h3>
      <p>We connect the tools cities already use — like traffic monitors, energy trackers or environmental sensors — into a shared European network. This makes it easier to collaborate, reuse solutions and give smaller communities access to cutting-edge technology.</p>
    </div>
    <div class="card">
      <div class="icon">🧪</div>
      <h3>Testing smart solutions in the real world</h3>
      <p>Through pilot projects, we support local teams to develop and test AI-driven services. These real-life pilots improve everyday life by making public services faster, decision-making smarter and cities more sustainable.</p>
    </div>
    <div class="card">
      <div class="icon">🤖</div>
      <h3>Expanding Europe’s toolbox with AI innovation</h3>
      <p>We are enriching the EU’s Local Digital Twin Toolbox with new AI-powered tools — from prediction models to self-organising systems — so cities can respond to challenges more quickly and effectively.</p>
    </div>
  </div>

  <!-- IMPACT -->
  <div class="block block-grey">
    <div class="sec-label">Impact for Europe</div>
    <h2 class="sec-title">Supporting Europe’s digital transformation</h2>
    <p>Europe’s digital transformation is often slowed down by high costs, complex rules and scattered expertise. LDT4SSC helps break down these barriers by:</p>
    <ul style="padding-left:18px; line-height:1.8;">
      <li>Bringing cities together to share solutions.</li>
      <li>Supporting open, ethical, people-centred technology.</li>
      <li>Creating fair digital markets with open standards.</li>
      <li>Working with the European Digital Infrastructure Consortium (EDIC) to build strong, connected systems across borders.</li>
    </ul>
    <p style="margin-top:20px;">This project is funded by the Digital Europe Programme and directly supports the EU’s vision of a digital, green and inclusive society.</p>
  </div>

  <!-- PARTNERS -->
  <div class="sec-label">Our Partners</div>
  <h2 class="sec-title">A pan-European partnership</h2>
  <p class="sec-sub">LDT4SSC brings together a diverse and experienced group of partners from across Europe. The consortium includes public research institutes, universities, non-profits, local authorities and open-source technology providers, all working together to advance interoperable Local Digital Twins and AI-driven services across Europe.</p>

  <div class="partners">
    <a class="partner" href="https://oascities.org" target="_blank"><img src="../images/partners/oasc.png"></a>
    <a class="partner" href="https://www.list.lu" target="_blank"><img src="../images/partners/list.png"></a>
    <a class="partner" href="https://www.fiware.org" target="_blank"><img src="../images/partners/fiware.png"></a>
    <a class="partner" href="https://www.kereval.com" target="_blank"><img src="../images/partners/kereval.png"></a>
    <a class="partner" href="https://taltech.ee" target="_blank"><img src="../images/partners/taltech.png"></a>

    <a class="partner" href="https://enoll.org" target="_blank"><img src="../images/partners/enoll.svg"></a>
    <a class="partner" href="https://www.cerema.fr" target="_blank"><img src="../images/partners/newceremalogo.png"></a>
    <a class="partner" href="https://technopolis-group.com" target="_blank"><img src="../images/partners/technopolis.png"></a>
    <a class="partner" href="https://www.libelium.com" target="_blank"><img src="../images/partners/libellium.jpg"></a>
    <a class="partner" href="https://www.ugent.be" target="_blank"><img src="../images/partners/ugent.png"></a>
  </div>

</div>
</div>
