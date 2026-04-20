---
title: "2nd Citiverse Assembly"
date: 2025-04-20
event_date: 2026-05-12
event_location: "Geneva, Switzerland"
type: "event"
---

<style>
/* Hide the layout-injected page title above the image */
.content h1:first-child,
.page-title,
h1.title,
article > h1:first-of-type {
  display: none !important;
}

.ev {
  font-family: Arial, Helvetica, sans-serif;
  color: #4C5562;
  font-size: 15px;
  line-height: 1.6;
  max-width: 900px;
  margin: 0 auto;
  padding: 0 24px 56px;

  --blue:       #1F75D6;
  --blue-pale:  #C8DFF5;
  --blue-tint:  #EBF4FD;
  --green:      #29A329;
  --green-pale: #C8E8C8;
  --green-tint: #EDF7E8;
  --yellow:     #F5B400;
  --yellow-pale:#FDE9A0;
  --yellow-tint:#FFFAE8;
  --grey:       #4C5562;
  --grey-mid:   #7D8896;
  --grey-pale:  #E0E3E8;
  --grey-tint:  #F5F6F8;
  --ink:        #1E2530;
}
.ev *, .ev *::before, .ev *::after { box-sizing: border-box; margin: 0; padding: 0; }
.ev a { color: var(--blue); text-decoration: none; }
.ev a:hover { text-decoration: underline; }

/* HERO IMAGE */
.ev .ev-hero-img {
  width: 100%;
  display: block;
  border-radius: 14px;
  margin-bottom: 32px;
}

/* LABEL */
.ev .ev-label {
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
.ev .ev-label::before {
  content: '';
  display: block;
  width: 22px; height: 2px;
  background: var(--green);
  border-radius: 2px;
  flex-shrink: 0;
}

/* TITLE */
.ev .ev-title {
  font-size: clamp(22px, 3vw, 36px);
  font-weight: 700;
  color: var(--ink);
  line-height: 1.15;
  margin-bottom: 24px;
}

/* META STRIP */
.ev .ev-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 32px;
}
.ev .ev-meta-pill {
  display: flex;
  align-items: center;
  gap: 8px;
  padding: 10px 18px;
  border-radius: 8px;
  font-size: 13.5px;
  font-weight: 600;
  border: 1.5px solid;
}
.ev .ev-meta-pill.date {
  background: var(--blue-tint);
  border-color: var(--blue-pale);
  color: var(--blue);
}
.ev .ev-meta-pill.place {
  background: var(--green-tint);
  border-color: var(--green-pale);
  color: var(--green);
}
.ev .ev-meta-pill svg {
  flex-shrink: 0;
  width: 15px; height: 15px;
}

/* INFO BLOCK */
.ev .ev-info-block {
  background: var(--yellow-tint);
  border: 1.5px solid var(--yellow-pale);
  border-left: 5px solid var(--yellow);
  border-radius: 10px;
  padding: 20px 24px;
  margin-bottom: 32px;
}
.ev .ev-info-block h3 {
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #9a7300;
  margin-bottom: 14px;
}
.ev .ev-info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 10px;
}
.ev .ev-info-item {
  background: #fff;
  border: 1.5px solid var(--yellow-pale);
  border-radius: 7px;
  padding: 10px 14px;
}
.ev .ev-info-item .dil {
  font-size: 11px;
  color: var(--grey-mid);
  text-transform: uppercase;
  letter-spacing: 0.06em;
  margin-bottom: 2px;
}
.ev .ev-info-item .div {
  font-size: 13.5px;
  font-weight: 700;
  color: var(--ink);
}

/* BODY TEXT */
.ev .ev-body {
  margin-bottom: 32px;
}
.ev .ev-body h3 {
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--grey-mid);
  margin-bottom: 10px;
}
.ev .ev-body p {
  margin-bottom: 16px;
  color: var(--grey);
  line-height: 1.75;
}
.ev .ev-body p:last-child {
  margin-bottom: 0;
}

/* DIVIDER */
.ev .ev-divider {
  height: 1px;
  background: var(--grey-pale);
  margin: 32px 0;
}

/* CTA BUTTONS */
.ev .ev-ctas {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}
.ev .ev-cta {
  background: var(--blue);
  color: #fff !important;
  font-size: 14.5px;
  font-weight: 700;
  padding: 14px 28px;
  border-radius: 8px;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  text-decoration: none !important;
  transition: background 0.2s;
}
.ev .ev-cta:hover {
  background: #1660b8;
}

@media (max-width: 600px) {
  .ev { padding: 0 14px 40px; }
  .ev .ev-meta { flex-direction: column; }
  .ev .ev-ctas { flex-direction: column; }
}
</style>

<div class="ev">

  <!-- HERO IMAGE -->
  <img class="ev-hero-img" src="/images/itu.png" alt="2nd Citiverse Assembly" />

  <!-- LABEL -->
  <div class="ev-label">Upcoming Event</div>

  <!-- TITLE -->
  <h1 class="ev-title">2nd Citiverse Assembly</h1>

  <!-- META PILLS -->
  <div class="ev-meta">
    <div class="ev-meta-pill date">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
      12 May 2026
    </div>
    <div class="ev-meta-pill place">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 13-9 13S3 17 3 10a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
      Geneva, Switzerland
    </div>
  </div>

  <!-- YELLOW INFO BLOCK -->
  <div class="ev-info-block">
    <h3>Key Information</h3>
    <div class="ev-info-grid">
      <div class="ev-info-item">
        <div class="dil">Organised by</div>
        <div class="div">ITU, European Commission, OASC &amp; UNICC</div>
      </div>
      <div class="ev-info-item">
        <div class="dil">Registration</div>
        <div class="div">Free of charge</div>
      </div>
    </div>
  </div>

  <!-- BODY -->
  <div class="ev-body">
    <h3>Description</h3>
    <p>Co-organised by ITU, the European Commission, OASC and UNICC, and supported by StandICT.eu 2029, the 2nd Citiverse Assembly convenes cities, governments, industry, standards bodies, research, and academia to strengthen global collaboration on the citiverse. The Assembly will share experiences from ongoing citiverse and local digital twin projects worldwide, present flagship deliverables of the Global Initiative on AI and Virtual Worlds – Discovering the Citiverse, and promote greater alignment across standards and implementation efforts.</p>
    <p>The programme will address fragmentation, support people-centred approaches, and explore practical pathways for collaborative citiverse standardisation.</p>
  </div>

  <div class="ev-divider"></div>

  <div class="ev-body">
    <h3>Target Audience</h3>
    <p>Participation is open to ITU Member States, Sector Members, Associates, Academia, and to any individual from a country that is a member of the ITU and who wishes to contribute to the work. This includes individuals who are also members of international, regional, and national organisations. Participation is free of charge.</p>
  </div>

  <div class="ev-divider"></div>

  <div class="ev-body">
    <h3>Venue</h3>
    <p>International Telecommunication Union (ITU) Headquarters<br>
    Place des Nations, 1211 Geneva 20, Switzerland</p>
  </div>

  <div class="ev-divider"></div>

  <!-- CTA -->
  <div class="ev-ctas">
    <a class="ev-cta" href="https://www.itu.int/metaverse/virtual-worlds/2nd-citiverse-assembly/" target="_blank" rel="noopener">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
      View programme &amp; register
    </a>
  </div>

</div>
