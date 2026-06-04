---
title: "Open Call 3 Info Session Materials Now Available"
date: 2026-06-04
type: "news"
---

<style>
.content h1:first-child,
.page-title,
h1.title,
article > h1:first-of-type {
  display: none !important;
}

.nw {
  font-family: Arial, Helvetica, sans-serif;
  color: #4C5562;
  font-size: 15px;
  line-height: 1.6;
  max-width: 900px;
  margin: 0 auto;
  padding: 0 24px 56px;

  --blue:        #1F75D6;
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
.nw *, .nw *::before, .nw *::after { box-sizing: border-box; margin: 0; padding: 0; }
.nw a { color: var(--blue); text-decoration: none; }
.nw a:hover { text-decoration: underline; }

.nw .nw-label {
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
.nw .nw-label::before {
  content: '';
  display: block;
  width: 22px; height: 2px;
  background: var(--blue);
  border-radius: 2px;
  flex-shrink: 0;
}

.nw .nw-title {
  font-size: clamp(22px, 3vw, 36px);
  font-weight: 700;
  color: var(--ink);
  line-height: 1.15;
  margin-bottom: 16px;
}

.nw .nw-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 32px;
}
.nw .nw-meta-pill {
  display: flex;
  align-items: center;
  gap: 8px;
  padding: 10px 18px;
  border-radius: 8px;
  font-size: 13.5px;
  font-weight: 600;
  border: 1.5px solid;
}
.nw .nw-meta-pill.date {
  background: var(--blue-tint);
  border-color: var(--blue-pale);
  color: var(--blue);
}
.nw .nw-meta-pill svg {
  flex-shrink: 0;
  width: 15px; height: 15px;
}

.nw .nw-intro {
  font-size: 16px;
  color: var(--grey);
  line-height: 1.8;
  margin-bottom: 32px;
  padding-bottom: 32px;
  border-bottom: 1px solid var(--grey-pale);
}

.nw .nw-body {
  font-size: 15px;
  color: var(--grey);
  line-height: 1.8;
  margin-bottom: 32px;
}

/* Work strand pills */
.nw .nw-strands {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 14px;
  margin-bottom: 32px;
}
.nw .nw-strand {
  border-radius: 10px;
  padding: 16px 18px;
  border: 1.5px solid;
}
.nw .nw-strand.blue   { background: var(--blue-tint);   border-color: var(--blue-pale); }
.nw .nw-strand.green  { background: var(--green-tint);  border-color: var(--green-pale); }
.nw .nw-strand.yellow { background: var(--yellow-tint); border-color: var(--yellow-pale); }
.nw .nw-strand .strand-num {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  margin-bottom: 4px;
}
.nw .nw-strand.blue   .strand-num { color: var(--blue); }
.nw .nw-strand.green  .strand-num { color: var(--green); }
.nw .nw-strand.yellow .strand-num { color: #9a7300; }
.nw .nw-strand .strand-title {
  font-size: 13.5px;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.4;
}

/* Material download cards */
.nw .nw-materials {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  margin-bottom: 32px;
}
.nw .nw-material-card {
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 18px 22px;
  border-radius: 10px;
  border: 1.5px solid;
  text-decoration: none !important;
  transition: box-shadow 0.2s, transform 0.15s;
  flex: 1;
  min-width: 220px;
}
.nw .nw-material-card:hover {
  box-shadow: 0 4px 16px rgba(31,117,214,0.12);
  transform: translateY(-2px);
  text-decoration: none !important;
}
.nw .nw-material-card.blue {
  background: var(--blue-tint);
  border-color: var(--blue-pale);
}
.nw .nw-material-card.outline {
  background: #fff;
  border-color: var(--grey-pale);
}
.nw .nw-material-card .mat-icon {
  width: 40px; height: 40px;
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0;
}
.nw .nw-material-card.blue .mat-icon   { background: var(--blue); }
.nw .nw-material-card.outline .mat-icon { background: var(--grey-tint); border: 1px solid var(--grey-pale); }
.nw .nw-material-card .mat-label {
  font-size: 11px; font-weight: 700; letter-spacing: 0.08em;
  text-transform: uppercase; margin-bottom: 2px;
}
.nw .nw-material-card.blue .mat-label    { color: var(--blue); }
.nw .nw-material-card.outline .mat-label { color: var(--grey-mid); }
.nw .nw-material-card .mat-title { font-size: 14px; font-weight: 700; color: var(--ink); }

/* CTA banner */
.nw .nw-cta {
  background: var(--yellow-tint);
  border: 1.5px solid var(--yellow-pale);
  border-left: 5px solid var(--yellow);
  border-radius: 10px;
  padding: 22px 26px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  flex-wrap: wrap;
}
.nw .nw-cta p { font-size: 14px; color: var(--grey); }
.nw .nw-cta a.btn {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  padding: 10px 18px;
  border-radius: 6px;
  font-size: 13.5px;
  font-weight: 700;
  background: var(--yellow);
  color: var(--ink) !important;
  text-decoration: none !important;
  white-space: nowrap;
  transition: filter 0.15s;
}
.nw .nw-cta a.btn:hover { filter: brightness(1.06); }

.nw .nw-divider {
  height: 1px;
  background: var(--grey-pale);
  margin: 32px 0;
}

@media (max-width: 600px) {
  .nw .nw-strands { grid-template-columns: 1fr; }
  .nw .nw-cta { flex-direction: column; align-items: flex-start; }
}
</style>

<div class="nw">

  <div class="nw-label">Project News</div>

  <h1 class="nw-title">Open Call 3 Info Session Materials Now Available</h1>

  <div class="nw-meta">
    <div class="nw-meta-pill date">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
      4 June 2026
    </div>
  </div>

  <p class="nw-intro">The recording and presentation slides from the LDT4SSC Open Call 3 Info Session, held on 22 May 2026, are now available. The session introduced the third and final round of open calls, covering all three Work Strands open for applications.</p>

  <p class="nw-body">The Info Session walked potential applicants through the call structure, eligibility requirements, and available support — including guidance on building a strong consortium. A dedicated Q&amp;A gave participants the opportunity to put questions directly to the project team. The recording and slides are available below for those who were unable to attend.</p>

  <div class="nw-strands">
    <div class="nw-strand blue">
      <div class="strand-num">Work Strand 1</div>
      <div class="strand-title">Interconnecting existing Local Digital Twins</div>
    </div>
    <div class="nw-strand green">
      <div class="strand-num">Work Strand 2</div>
      <div class="strand-title">Creation of LDTs based on common needs</div>
    </div>
    <div class="nw-strand yellow">
      <div class="strand-num">Work Strand 3</div>
      <div class="strand-title">Adding new and advanced AI services to the EU LDT Toolbox</div>
    </div>
  </div>

  <div class="nw-materials">
    <a href="https://youtu.be/QBZLbNLpuII" class="nw-material-card blue" target="_blank">
      <div class="mat-icon">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8" fill="#fff" stroke="none"/></svg>
      </div>
      <div>
        <div class="mat-label">Recording</div>
        <div class="mat-title">Watch on YouTube</div>
      </div>
    </a>
    <a href="https://ldt4ssc.eu/documents/info-session-three.pdf" class="nw-material-card outline" target="_blank">
      <div class="mat-icon">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#4C5562" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/></svg>
      </div>
      <div>
        <div class="mat-label">Slides</div>
        <div class="mat-title">Download Presentation (PDF)</div>
      </div>
    </a>
  </div>

  <div class="nw-divider"></div>

  <div class="nw-cta">
    <p>Open Call 3 is open until <strong>13 July 2026 · 23:59 CEST</strong>. Full details and application documents are available on the call page.</p>
    <a href="https://ldt4ssc.eu/call-three/" class="btn">View Open Call 3 &rarr;</a>
  </div>

</div>
