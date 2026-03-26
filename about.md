---
title: About
layout: fullwidth
description: About the Project
---

<style>
/* ── Full-width wrapper without hiding dropdowns ── */
.oc2-escape {
  position: relative;  /* allows dropdowns to show */
  width: 100%;
  margin-left: 0;
  margin-right: 0;
  z-index: 1;
  overflow: visible;   /* critical to prevent drop-down from being cut */
}

/* ── Base styles ── */
.oc2 {
  font-family: Arial, Helvetica, sans-serif;
  color: #4C5562;
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 32px;
}
.oc2 *, .oc2 *::before, .oc2 *::after { box-sizing: border-box; margin: 0; padding: 0; }
.oc2 a { text-decoration: none; color: inherit; }

/* ── Palette ── */
.oc2 {
  --blue:#1F75D6; --blue-mid:#5497DC; --blue-pale:#C8DFF5; --blue-tint:#EBF4FD;
  --green:#29A329; --green-pale:#C8E8C8; --green-tint:#EDF7E8;
  --yellow:#F5B400; --yellow-pale:#F5D980; --yellow-tint:#FEF7DC;
  --grey:#4C5562; --grey-mid:#7A8494; --grey-pale:#D8DCE3; --grey-tint:#F2F3F5;
}

/* ── HERO ── */
.hero {
  background: linear-gradient(135deg, var(--blue-tint), #ffffff);
  border: 1px solid var(--blue-pale);
  border-radius: 14px;
  padding: 52px;
  margin-bottom: 48px;
  position: relative;
}
.hero h1 {
  font-size: clamp(28px,3vw,44px);
  font-weight: 700;
  line-height: 1.1;
}
.hero .accent { color: var(--blue); }
.hero p { max-width: 720px; margin-top: 12px; color: var(--grey-mid); }

/* subtle background pattern */
.hero::after {
  content:'';
  position:absolute;
  top:0; left:0;
  width:100%; height:100%;
  background: radial-gradient(circle, rgba(255,255,255,0.2) 1px, transparent 1px);
  background-size: 40px 40px;
  pointer-events:none;
}

/* ── Sections ── */
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
  position: relative;
}
.sec-title::after {
  content: '';
  position: absolute;
  bottom: -6px;
  left: 0;
  width: 48px;
  height: 4px;
  background: var(--blue);
  border-radius: 2px;
}
.sec-sub { color: var(--grey-mid); margin-bottom: 28px; }

/* ── Grid / Cards ── */
.grid {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  gap: 20px;
  margin-bottom: 32px;
}
.card {
  background:#ffffff;
  border-radius:12px;
  padding:28px;
  transition:.2s;
  position: relative;
  border-left: 6px solid var(--blue-tint);
}
.card:nth-child(2) { border-left-color: var(--green-tint); }
.card:nth-child(3) { border-left-color: var(--yellow-tint); }
.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
}
.icon {
  font-size: 22px;
  margin-bottom: 10px;
}
.card h3 { font-size:16px; margin-bottom:8px; }
.card p { font-size:14px; color: var(--grey-mid); }

/* ── Blocks ── */
.block {
  border-radius:14px;
  padding:36px;
  margin-top:30px;
  margin-bottom:40px; /* extra space under block */
}
.block-grey { background: var(--grey-tint); }
.block-blue { background: var(--blue-tint); }

/* ── Partners ── */
.partners {
  display:grid;
  grid-template-columns: repeat(5,1fr);
  gap: 22px;
  margin-top: 30px;
  margin-bottom:50px; /* extra spacing under partners */
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
  border-color: var(--blue-mid);
  box-shadow:0 6px 18px rgba(31,117,214,0.08);
}
.partner img {
  max-width:100%;
  max-height:42px;
  filter: none; /* show original colors */
  opacity:1;
}

/* ── Responsive ── */
@media(max-width:900px){
  .grid { grid-template-columns:1fr; }
  .partners { grid-template-columns: repeat(2,1fr); }
  .hero { padding:28px; }
}
</style>

<div class="oc2-escape">
<div class="oc2">

<!-- HERO -->
<div class="hero">
  <div class="sec-label">About</div>
  <h1>Building Europe’s <span class="accent">Digital Twin Ecosystem</span></h1>
  <p>
    LDT4SSC enables cities and communities across Europe to use data and Artificial Intelligence to make better decisions — improving sustainability, resilience and quality of life.
  </p>
</div>

<!-- WHAT WE DO -->
<div class="sec-label">Our Work</div>
<h2 class="sec-title">From data to smarter cities</h2>
<p class="sec-sub">
Across Europe, cities and communities face similar challenges: how to use energy more efficiently, reduce pollution, improve public services and adapt to climate change.
</p>

<p class="sec-sub">
LDT4SSC — short for Local Digital Twins for Smart Sustainable Cities — helps cities meet these challenges by sharing powerful digital tools called Local Digital Twins. Think of them as digital copies of real places. They use data and Artificial Intelligence (AI) to help local governments make smarter, faster decisions — for example, predicting traffic, planning green spaces or improving waste collection.
</p>

<p class="sec-sub"><strong>Linking digital twins across Europe</strong></p>
<p class="sec-sub">
We connect the tools cities already use — like traffic monitors, energy trackers or environmental sensors — into a shared European network. This makes it easier to collaborate, reuse solutions and give smaller communities access to cutting-edge technology.
</p>

<p class="sec-sub"><strong>Testing smart solutions in the real world</strong></p>
<p class="sec-sub">
Through pilot projects, we support local teams to develop and test AI-driven services. These real-life pilots improve everyday life by making public services faster, decision-making smarter and cities more sustainable.
</p>

<p class="sec-sub"><strong>Expanding Europe’s toolbox with AI innovation</strong></p>
<p class="sec-sub">
We are enriching the EU’s Local Digital Twin Toolbox with new AI-powered tools — from prediction models to self-organising systems — so cities can respond to challenges more quickly and effectively.
</p>

<!-- IMPACT -->
<div class="block block-grey">
  <div class="sec-label">Impact</div>
  <h2 class="sec-title">Supporting Europe’s digital transformation</h2>
  <p class="sec-sub">
Europe’s digital transformation is often slowed down by high costs, complex rules and scattered expertise. LDT4SSC helps break down these barriers by:
  </p>

  <ul style="padding-left:18px; line-height:1.8;">
    <li>Bringing cities together to share solutions.</li>
    <li>Supporting open, ethical, people-centred technology.</li>
    <li>Creating fair digital markets with open standards.</li>
    <li>Working with the European Digital Infrastructure Consortium (EDIC) to build strong, connected systems across borders.</li>
  </ul>

  <p style="margin-top:30px;">
This project is funded by the Digital Europe Programme and directly supports the EU’s vision of a digital, green and inclusive society.
  </p>
</div>

<!-- PARTNERS -->
<div class="sec-label">Consortium</div>
<h2 class="sec-title">A pan-European partnership</h2>
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
