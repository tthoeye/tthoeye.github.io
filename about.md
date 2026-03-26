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
/* ── Break out of container for full-width ── */
.oc2-escape {
  position: relative;
  left: 50%;
  margin-left: -50vw;
  width: 100vw;
  z-index: 0; /* ensures dropdowns appear above */
}

/* ── Scoped styles for .oc2 ── */
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

/* ── Brand palette ── */
.oc2 {
  --blue: #1F75D6;
  --blue-tint: #EBF4FD;
  --green: #29A329;
  --green-tint: #EDF7E8;
  --yellow: #F5B400;
  --yellow-tint: #FEF7DC;
  --grey: #4C5562;
  --grey-mid: #7A8494;
  --grey-pale: #D8DCE3;
  --grey-tint: #F2F3F5;
  --ink: #4C5562;
}

/* ── HERO ── */
.oc2 .hero {
  background: linear-gradient(135deg, var(--green-tint), var(--yellow-tint));
  border: 1.5px solid var(--green);
  border-radius: 14px;
  padding: 48px;
  margin-bottom: 48px;
  z-index: 1;
}
.oc2 .hero h1 {
  font-size: clamp(26px, 3vw, 44px);
  font-weight: 700;
  color: var(--ink);
  line-height: 1.1;
  margin-bottom: 16px;
}
.oc2 .hero h1 .accent { color: var(--green); }
.oc2 .hero-sub {
  font-size: 15px;
  color: var(--grey-mid);
  line-height: 1.7;
  margin-bottom: 28px;
  max-width: 720px;
}

/* ── Section labels ── */
.oc2 .sec-label {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.13em;
  text-transform: uppercase;
  color: var(--green);
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 10px;
}
.oc2 .sec-label::before {
  content: '';
  display: block;
  width: 22px; height: 2px;
  background: var(--green);
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

/* ── BLOCKS ── */
.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 48px; z-index: 1; }
.oc2 .block-green { background: var(--green-tint); border: 1.5px solid var(--green); }
.oc2 .block-yellow { background: var(--yellow-tint); border: 1.5px solid var(--yellow); }

/* ── PARTNERS GRID ── */
.oc2 .partners {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 22px;
  margin-top: 32px;
  margin-bottom: 60px;
  z-index: 1;
}
.oc2 .partner {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 16px;
  border-radius: 10px;
  background: #fff;
  border: 1px solid var(--grey-pale);
  transition: .2s;
}
.oc2 .partner:hover {
  border-color: var(--green);
  box-shadow: 0 6px 18px rgba(41,163,41,0.08);
}
.oc2 .partner img { max-width: 100%; max-height: 42px; filter: none; opacity: 1; }

/* ── RESPONSIVE ── */
@media(max-width: 900px){
  .oc2 .partners { grid-template-columns: repeat(2,1fr); }
  .oc2 .hero { padding: 28px; }
  .oc2 .block { padding: 28px; }
}
</style>

<div class="oc2-escape">
<div class="oc2">

  <!-- HERO -->
  <div class="hero">
    <div class="sec-label">About</div>
    <h1>Our Work in <span class="accent">Smart Sustainable Cities</span></h1>
    <p class="hero-sub">
      Across Europe, cities and communities face similar challenges: how to use energy more efficiently, reduce pollution, improve public services and adapt to climate change.
    </p>
  </div>

  <!-- WHAT WE DO -->
  <div class="sec-label">Our Work</div>
  <h2 class="sec-title">LDT4SSC Project</h2>
  <p class="sec-sub">
    LDT4SSC — short for Local Digital Twins for Smart Sustainable Cities — helps cities meet these challenges by sharing powerful digital tools called Local Digital Twins. Think of them as digital copies of real places. They use data and Artificial Intelligence (AI) to help local governments make smarter, faster decisions — for example, predicting traffic, planning green spaces or improving waste collection.
  </p>

  <div class="block block-green">
    <h3>Linking digital twins across Europe</h3>
    <p>We connect the tools cities already use — like traffic monitors, energy trackers or environmental sensors — into a shared European network. This makes it easier to collaborate, reuse solutions and give smaller communities access to cutting-edge technology.</p>
    <h3>Testing smart solutions in the real world</h3>
    <p>Through pilot projects, we support local teams to develop and test AI-driven services. These real-life pilots improve everyday life by making public services faster, decision-making smarter and cities more sustainable.</p>
    <h3>Expanding Europe’s toolbox with AI innovation</h3>
    <p>We are enriching the EU’s Local Digital Twin Toolbox with new AI-powered tools — from prediction models to self-organising systems — so cities can respond to challenges more quickly and effectively.</p>
  </div>

  <!-- IMPACT -->
  <div class="block block-yellow">
    <div class="sec-label">Impact for Europe</div>
    <p class="sec-sub">
      Europe’s digital transformation is often slowed down by high costs, complex rules and scattered expertise. LDT4SSC helps break down these barriers by:
    </p>
    <ul style="padding-left:18px; line-height:1.8;">
      <li>Bringing cities together to share solutions</li>
      <li>Supporting open, ethical, people-centred technology</li>
      <li>Creating fair digital markets with open standards</li>
      <li>Working with the European Digital Infrastructure Consortium (EDIC) to build strong, connected systems across borders</li>
    </ul>
    <p style="margin-top:20px;">
      This project is funded by the Digital Europe Programme and directly supports the EU’s vision of a digital, green and inclusive society.
    </p>
  </div>

  <!-- PARTNERS -->
  <div class="sec-label">Our Partners</div>
  <h2 class="sec-title">Consortium</h2>
  <p class="sec-sub">
    LDT4SSC brings together a diverse and experienced group of partners from across Europe. The consortium includes public research institutes, universities, non-profits, local authorities and open-source technology providers, all working together to advance interoperable Local Digital Twins and AI-driven services across Europe.
  </p>

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
