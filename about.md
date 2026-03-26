---
title: About
layout: fullwidth
description: About the Project
---

<style>
.oc2-escape {
  position: relative;
  left: 50%;
  margin-left: -50vw;
  width: 100vw;
}
.oc2 {
  font-family: Arial, Helvetica, sans-serif;
  color: #4C5562;
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 32px;
}

/* palette */
.oc2 {
  --blue:#1F75D6; --blue-mid:#5497DC; --blue-pale:#C8DFF5; --blue-tint:#EBF4FD;
  --green:#29A329; --yellow:#F5B400;
  --grey:#4C5562; --grey-mid:#7A8494; --grey-pale:#D8DCE3; --grey-tint:#F2F3F5;
}

/* hero */
.hero {
  background: linear-gradient(135deg, var(--blue-tint), #ffffff);
  border: 1px solid var(--blue-pale);
  border-radius: 14px;
  padding: 52px;
  margin-bottom: 48px;
}
.hero h1 {
  font-size: clamp(28px,3vw,44px);
  font-weight: 700;
}
.hero .accent { color: var(--blue); }
.hero p { max-width: 720px; margin-top: 12px; }

/* sections */
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
  line-height:1.7;
}

/* blocks */
.block {
  border-radius:14px;
  padding:36px;
  margin-top:30px;
}
.block-grey { background: var(--grey-tint); }
.block-blue { background: var(--blue-tint); }

/* partners */
.partners {
  display:grid;
  grid-template-columns: repeat(5,1fr);
  gap: 22px;
  margin-top:24px;
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
  filter: grayscale(100%);
  opacity:.85;
}
.partner:hover img {
  filter:none;
  opacity:1;
}

/* lists */
ul { padding-left:18px; line-height:1.8; }
li { margin-bottom:8px; }

/* ── Stats strip ── */
.stats {
  display:grid;
  grid-template-columns: repeat(4,1fr);
  gap:20px;
  margin:30px 0 50px;
}
.stat {
  background:#fff;
  border:1px solid var(--grey-pale);
  border-radius:12px;
  padding:24px;
  text-align:center;
}
.num {
  font-size:22px;
  font-weight:700;
  color: var(--blue);
}
.label {
  font-size:12px;
  color: var(--grey-mid);
  margin-top:4px;
}

/* ── Timeline ── */
.timeline {
  margin-top:20px;
  border-left:2px solid var(--blue-pale);
  padding-left:20px;
}
.t-item {
  position:relative;
  margin-bottom:20px;
}
.t-dot {
  position:absolute;
  left:-27px;
  top:4px;
  width:10px;
  height:10px;
  background: var(--blue);
  border-radius:50%;
}
.t-content strong {
  display:block;
  font-size:14px;
}
.t-content p {
  font-size:13px;
  color: var(--grey-mid);
}

/* responsive */
@media(max-width:900px){
  .partners { grid-template-columns: repeat(2,1fr); }
  .oc2 { padding:0 16px; }
  .stats { grid-template-columns: 1fr 1fr; }
}
</style>

<div class="oc2-escape">
<div class="oc2">

<!-- HERO -->
<div class="hero">
  <div class="sec-label">About</div>
  <h1 class="sec-title">Our Work</h1>
</div>

<!-- STATS -->
<div class="stats">
  <div class="stat">
    <div class="num">10+</div>
    <div class="label">Partners</div>
  </div>
  <div class="stat">
    <div class="num">8</div>
    <div class="label">Countries</div>
  </div>
  <div class="stat">
    <div class="num">2025–2028</div>
    <div class="label">Duration</div>
  </div>
  <div class="stat">
    <div class="num">EU</div>
    <div class="label">Funded</div>
  </div>
</div>

<!-- ORIGINAL CONTENT START -->
<p class="sec-sub">
Across Europe, cities and communities face similar challenges: how to use energy more efficiently, reduce pollution, improve public services and adapt to climate change.
</p>
<p class="sec-sub">
LDT4SSC — short for Local Digital Twins for Smart Sustainable Cities — helps cities meet these challenges by sharing powerful digital tools called Local Digital Twins. Think of them as digital copies of real places. They use data and Artificial Intelligence (AI) to help local governments make smarter, faster decisions — for example, predicting traffic, planning green spaces or improving waste collection.
</p>

<h2 class="sec-title">Linking digital twins across Europe</h2>
<p class="sec-sub">
We connect the tools cities already use — like traffic monitors, energy trackers or environmental sensors — into a shared European network. This makes it easier to collaborate, reuse solutions and give smaller communities access to cutting-edge technology.
</p>

<h2 class="sec-title">Testing smart solutions in the real world</h2>
<p class="sec-sub">
Through pilot projects, we support local teams to develop and test AI-driven services. These real-life pilots improve everyday life by making public services faster, decision-making smarter and cities more sustainable.
</p>

<h2 class="sec-title">Expanding Europe’s toolbox with AI innovation</h2>
<p class="sec-sub">
We are enriching the EU’s Local Digital Twin Toolbox with new AI-powered tools — from prediction models to self-organising systems — so cities can respond to challenges more quickly and effectively.
</p>

<h2 class="sec-title">Impact for Europe</h2>
<p class="sec-sub">
Europe’s digital transformation is often slowed down by high costs, complex rules and scattered expertise. LDT4SSC helps break down these barriers by:
</p>
<ul>
  <li>Bringing cities together to share solutions.</li>
  <li>Supporting open, ethical, people-centred technology.</li>
  <li>Creating fair digital markets with open standards.</li>
  <li>Working with the European Digital Infrastructure Consortium (EDIC) to build strong, connected systems across borders.</li>
</ul>
<p class="sec-sub">
This project is funded by the Digital Europe Programme and directly supports the EU’s vision of a digital, green and inclusive society.
</p>

<h2 class="sec-title">Our Partners</h2>
<p class="sec-sub">
LDT4SSC brings together a diverse and experienced group of partners from across Europe. The consortium includes public research institutes, universities, non-profits, local authorities and open-source technology providers, all working together to advance interoperable Local Digital Twins and AI-driven services across Europe. This collaboration is made possible with the support of the European Union as the funding authority, ensuring alignment with broader EU digital and innovation priorities.
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
<!-- ORIGINAL CONTENT END -->

<!-- TIMELINE -->
<div class="block block-blue">
  <div class="sec-label">Timeline</div>
  <h2 class="sec-title">Project roadmap</h2>
  <div class="timeline">
    <div class="t-item">
      <div class="t-dot"></div>
      <div class="t-content">
        <strong>June 2025</strong>
        <p>Project launch and consortium alignment</p>
      </div>
    </div>

    <div class="t-item">
      <div class="t-dot"></div>
      <div class="t-content">
        <strong>2025–2026</strong>
        <p>First open calls and pilot deployment</p>
      </div>
    </div>

    <div class="t-item">
      <div class="t-dot"></div>
      <div class="t-content">
        <strong>2026–2027</strong>
        <p>Scaling AI tools and cross-city collaboration</p>
      </div>
    </div>

    <div class="t-item">
      <div class="t-dot"></div>
      <div class="t-content">
        <strong>2028</strong>
        <p>Final results, impact validation and EU-wide adoption</p>
      </div>
    </div>
  </div>
</div>

</div>
</div>
