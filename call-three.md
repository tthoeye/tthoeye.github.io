---
layout: fullwidth
permalink: /call-three/
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

.oc2 .banner {
  background: var(--green-tint);
  color: var(--ink);
  text-align: center;
  padding: 11px 20px;
  font-size: 13.5px;
  font-weight: 700;
  border-radius: 8px;
  margin-bottom: 12px;
  border: 2px solid var(--green-pale);
}

.oc2 .banner-yellow {
  background: var(--yellow-tint);
  border: 2px solid var(--yellow-pale);
  border-left: 5px solid var(--yellow);
  border-radius: 8px;
  margin-bottom: 28px;
  padding: 11px 20px;
  font-size: 13.5px;
  font-weight: 700;
  color: var(--ink);
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  flex-wrap: wrap;
}
.oc2 .banner-yellow a {
  background: var(--yellow);
  color: var(--ink) !important;
  font-size: 13px;
  font-weight: 700;
  padding: 8px 16px;
  border-radius: 6px;
  text-decoration: none;
  white-space: nowrap;
  flex-shrink: 0;
  transition: filter 0.15s;
}
.oc2 .banner-yellow a:hover { filter: brightness(1.08); }

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
.oc2 .sec-title { font-size: clamp(22px, 2.8vw, 34px); font-weight: 700; color: var(--ink); line-height: 1.15; margin-bottom: 10px; }
.oc2 .sec-sub   { font-size: 15px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 28px; }
.oc2 .sec-divider { height: 1px; background: var(--grey-pale); margin: 8px 0 32px; }

.oc2 .btn { display: inline-flex; align-items: center; gap: 7px; padding: 11px 20px; border-radius: 6px; font-family: Arial, Helvetica, sans-serif; font-size: 14px; font-weight: 700; transition: filter 0.15s, transform 0.15s; cursor: pointer; line-height: 1; }
.oc2 .btn:hover { filter: brightness(1.08); transform: translateY(-1px); }
.oc2 .btn-blue   { background: var(--blue);   color: #fff !important; }
.oc2 .btn-green  { background: var(--green);  color: #fff !important; }
.oc2 .btn-yellow { background: var(--yellow); color: var(--ink) !important; }
.oc2 .btn-outline { background: #fff; border: 2px solid var(--blue); color: var(--blue) !important; }
.oc2 .btn-outline:hover { background: var(--blue-tint); filter: none; }

.oc2 .hero {
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-radius: 14px;
  padding: 48px;
  display: grid;
  grid-template-columns: 1fr 260px;
  gap: 48px;
  align-items: center;
  margin-bottom: 40px;
}
.oc2 .hero-badge { display: inline-flex; align-items: center; gap: 8px; background: var(--green-pale); border: 1.5px solid var(--green); color: var(--green); font-size: 12px; font-weight: 700; letter-spacing: 0.07em; text-transform: uppercase; padding: 5px 12px; border-radius: 100px; margin-bottom: 18px; }
.oc2 .hero-badge .dot { width: 7px; height: 7px; background: var(--green); border-radius: 50%; animation: pulse 1.5s infinite; }
@keyframes pulse { 0%, 100% { opacity: 1; } 50% { opacity: 0.4; } }
.oc2 .hero h1 { font-family: Arial, Helvetica, sans-serif !important; font-size: clamp(26px, 3vw, 44px) !important; font-weight: 700 !important; color: var(--ink) !important; line-height: 1.1 !important; margin-bottom: 16px !important; border: none !important; padding: 0 !important; }
.oc2 .hero h1 .accent { color: var(--blue); }
.oc2 .hero-sub { font-size: 15px; color: var(--grey); line-height: 1.7; margin-bottom: 28px; }
.oc2 .hero-btns { display: flex; gap: 12px; flex-wrap: wrap; margin-bottom: 32px; }
.oc2 .hero-stats { display: grid; grid-template-columns: repeat(3,1fr); border: 1.5px solid var(--blue-pale); border-radius: 10px; overflow: hidden; background: #fff; }
.oc2 .stat { padding: 16px 18px; border-right: 1.5px solid var(--blue-pale); }
.oc2 .stat:last-child { border-right: none; }
.oc2 .stat-val { font-size: 24px; font-weight: 700; color: var(--blue); line-height: 1; }
.oc2 .stat-lbl { font-size: 11px; color: var(--grey-mid); margin-top: 3px; text-transform: uppercase; letter-spacing: 0.06em; }
.oc2 .hero-diagram svg { width: 100%; height: auto; display: block; }

.oc2 .strands-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 18px; margin-bottom: 36px; }
.oc2 .why-grid     { display: grid; grid-template-columns: repeat(2,1fr); gap: 16px; }
.oc2 .info-inner   { display: grid; grid-template-columns: 1fr 1fr; gap: 32px; align-items: start; }

.oc2 .strand-intro { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 10px; padding: 28px 24px; transition: box-shadow 0.2s; }
.oc2 .strand-intro:hover { box-shadow: 0 6px 20px rgba(31,117,214,0.10); }
.oc2 .strand-intro.si-blue   { border-top: 4px solid var(--blue); }
.oc2 .strand-intro.si-green  { border-top: 4px solid var(--green); }
.oc2 .strand-intro.si-yellow { border-top: 4px solid var(--yellow); }
.oc2 .strand-num { font-size: 40px; font-weight: 700; line-height: 1; margin-bottom: 8px; }
.oc2 .si-blue   .strand-num { color: var(--blue-pale); }
.oc2 .si-green  .strand-num { color: var(--green-pale); }
.oc2 .si-yellow .strand-num { color: var(--yellow-pale); }
.oc2 .strand-intro h3 { font-size: 16px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .strand-intro p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey   { background: var(--grey-tint);   border: 1.5px solid var(--grey-pale); }
.oc2 .block-blue   { background: var(--blue-tint);   border: 1.5px solid var(--blue-pale); }
.oc2 .block-green  { background: var(--green-tint);  border: 1.5px solid var(--green-pale); }
.oc2 .block-yellow { background: var(--yellow-tint); border: 1.5px solid var(--yellow-pale); }

.oc2 .why-card { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 10px; padding: 24px; display: flex; gap: 16px; align-items: flex-start; transition: border-color 0.2s, box-shadow 0.2s; }
.oc2 .why-card:hover { border-color: var(--blue-mid); box-shadow: 0 4px 16px rgba(31,117,214,0.09); }
.oc2 .why-icon { width: 42px; height: 42px; border-radius: 10px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
.oc2 .wi-blue   { background: var(--blue-tint); }
.oc2 .wi-green  { background: var(--green-tint); }
.oc2 .wi-yellow { background: var(--yellow-tint); }
.oc2 .wi-grey   { background: var(--grey-pale); }
.oc2 .why-body h3 { font-size: 15px !important; font-weight: 700; color: var(--ink); margin-bottom: 5px !important; }
.oc2 .why-body p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

.oc2 .timeline { display: grid; grid-template-columns: repeat(3,1fr); position: relative; }
.oc2 .timeline::before { content: ''; position: absolute; top: 12px; left: 12px; right: 12px; height: 2px; background: linear-gradient(90deg, var(--blue), var(--yellow), var(--green)); }
.oc2 .tl-item { position: relative; padding-top: 36px; padding-right: 20px; }
.oc2 .tl-dot { position: absolute; top: 5px; left: 0; width: 14px; height: 14px; border-radius: 50%; border: 3px solid var(--blue-tint); }
.oc2 .tl-item:nth-child(1) .tl-dot { background: var(--blue); }
.oc2 .tl-item:nth-child(2) .tl-dot { background: var(--yellow); }
.oc2 .tl-item:nth-child(3) .tl-dot { background: var(--green); }
.oc2 .tl-date  { font-size: 11px; font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase; margin-bottom: 5px; }
.oc2 .tl-item:nth-child(1) .tl-date { color: var(--blue); }
.oc2 .tl-item:nth-child(2) .tl-date { color: #b07f00; }
.oc2 .tl-item:nth-child(3) .tl-date { color: var(--green); }
.oc2 .tl-title { font-size: 15px; font-weight: 700; color: var(--ink); margin-bottom: 4px; }
.oc2 .tl-desc  { font-size: 13px; color: var(--grey-mid); line-height: 1.6; }
.oc2 .tl-item.tl-upcoming .tl-dot { background: var(--grey-pale); border-color: var(--blue-tint); }
.oc2 .tl-item.tl-upcoming .tl-title { color: var(--grey-mid); }

.oc2 .glance { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 10px; overflow: hidden; }
.oc2 .glance-head { background: var(--blue); color: #fff; padding: 12px 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.09em; text-transform: uppercase; }
.oc2 .glance-row { display: flex; justify-content: space-between; align-items: center; padding: 11px 20px; border-bottom: 1px solid var(--grey-pale); font-size: 13.5px; }
.oc2 .glance-row:last-child { border-bottom: none; }
.oc2 .gr-key { color: var(--grey-mid); }
.oc2 .gr-val { font-weight: 700; color: var(--ink); }
.oc2 .gr-open { color: var(--green) !important; }

.oc2 .doc-strand { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 10px; padding: 24px 28px; margin-bottom: 16px; }
.oc2 .doc-strand.ds-blue   { border-left: 4px solid var(--blue); }
.oc2 .doc-strand.ds-green  { border-left: 4px solid var(--green); }
.oc2 .doc-strand.ds-yellow { border-left: 4px solid var(--yellow); }
.oc2 .doc-strand.ds-grey   { border-left: 4px solid var(--grey-mid); }
.oc2 .doc-strand-label { font-size: 11px; font-weight: 700; letter-spacing: 0.10em; text-transform: uppercase; margin-bottom: 6px; }
.oc2 .ds-blue   .doc-strand-label { color: var(--blue); }
.oc2 .ds-green  .doc-strand-label { color: var(--green); }
.oc2 .ds-yellow .doc-strand-label { color: #9a7300; }
.oc2 .ds-grey   .doc-strand-label { color: var(--grey-mid); }
.oc2 .doc-strand h3 { font-size: 15px; font-weight: 700; color: var(--ink); margin-bottom: 14px; }
.oc2 .doc-strand p.doc-note { font-size: 13px; color: var(--grey-mid); line-height: 1.6; margin-bottom: 14px; }
.oc2 .doc-buttons { display: flex; flex-wrap: wrap; gap: 8px; }
.oc2 .doc-btn { display: inline-flex; align-items: center; gap: 5px; font-size: 12.5px; font-weight: 600; padding: 6px 12px; border-radius: 5px; text-decoration: none; transition: background 0.15s, border-color 0.15s; }
.oc2 .ds-blue   .doc-btn { background: var(--blue-tint);   border: 1px solid var(--blue-pale);   color: var(--blue) !important; }
.oc2 .ds-blue   .doc-btn:hover { background: var(--blue-pale);   border-color: var(--blue-mid); }
.oc2 .ds-green  .doc-btn { background: var(--green-tint);  border: 1px solid var(--green-pale);  color: var(--green) !important; }
.oc2 .ds-green  .doc-btn:hover { background: var(--green-pale);  border-color: var(--green); }
.oc2 .ds-yellow .doc-btn { background: var(--yellow-tint); border: 1px solid var(--yellow-pale); color: #9a7300 !important; }
.oc2 .ds-yellow .doc-btn:hover { background: var(--yellow-pale); border-color: var(--yellow); }
.oc2 .ds-grey   .doc-btn { background: var(--grey-tint);   border: 1px solid var(--grey-pale);   color: var(--grey) !important; }
.oc2 .ds-grey   .doc-btn:hover { background: var(--grey-pale); border-color: var(--grey-mid); }

.oc2 .cta-grid { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px; }
.oc2 .cta-card { border-radius: 12px; padding: 32px; display: flex; flex-direction: column; gap: 16px; }
.oc2 .cta-card-blue   { background: var(--blue-tint);   border: 1.5px solid var(--blue-pale); }
.oc2 .cta-card-green  { background: var(--green-tint);  border: 1.5px solid var(--green-pale); }
.oc2 .cta-card-yellow { background: var(--yellow-tint); border: 1.5px solid var(--yellow-pale); }
.oc2 .cta-card h3 { font-size: 15px !important; font-weight: 700; color: var(--ink); margin: 0 !important; }
.oc2 .cta-card p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; flex: 1; }
.oc2 .cta-links { display: flex; flex-direction: column; gap: 8px; }
.oc2 .cta-link { display: flex; align-items: center; gap: 10px; padding: 10px 14px; background: #fff; border-radius: 7px; font-size: 13px; font-weight: 700; transition: background 0.15s; }
.oc2 .cta-card-blue   .cta-link { border: 1.5px solid var(--blue-pale);   color: var(--blue) !important; }
.oc2 .cta-card-blue   .cta-link:hover { background: var(--blue-pale); }
.oc2 .cta-card-green  .cta-link { border: 1.5px solid var(--green-pale);  color: var(--green) !important; }
.oc2 .cta-card-green  .cta-link:hover { background: var(--green-pale); }
.oc2 .cta-card-yellow .cta-link { border: 1.5px solid var(--yellow-pale); color: #9a7300 !important; }
.oc2 .cta-card-yellow .cta-link:hover { background: var(--yellow-pale); }

@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .hero { grid-template-columns: 1fr; padding: 28px; }
  .oc2 .hero-diagram { display: none; }
  .oc2 .strands-grid, .oc2 .why-grid, .oc2 .info-inner, .oc2 .cta-grid { grid-template-columns: 1fr; }
  .oc2 .timeline { grid-template-columns: 1fr; }
  .oc2 .timeline::before { display: none; }
  .oc2 .tl-item { padding-top: 0; padding-left: 24px; padding-bottom: 20px; }
  .oc2 .tl-dot  { top: 2px; left: 0; }
  .oc2 .block   { padding: 24px; }
  .oc2 .banner-yellow { flex-direction: column; align-items: flex-start; }
}
</style>

<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <div class="banner">
    Open Call 3 is now <strong>open</strong> — Submit your application by <strong>13 July 2026 · 23:59 CEST</strong>
  </div>

  <div class="banner-yellow">
    <span>Looking for consortium partners? Join the <strong>LDT4SSC Matchmaking Event</strong> on <strong>11 June 2026, 10:30–12:30 CET</strong></span>
    <a href="https://ldt4ssc.eu/services/matchmaking-three/">Register Now &rarr;</a>
  </div>

  <div class="hero">
    <div>
      <div class="hero-badge"><span class="dot"></span> Open Call 3 · Status: Open</div>
      <h1>Third Round of <span class="accent">Open Calls</span></h1>
      <p class="hero-sub">The Local Digital Twins for Smart and Sustainable Communities (LDT4SSC) project, funded by the Digital Europe Programme (DEP), invites applications for its third Open Call across all three Work Strands — interconnecting, creating and enhancing Local Digital Twins across Europe.</p>
      <div class="hero-btns">
        <a href="mailto:applications@ldt4ssc.eu" class="btn btn-green">Apply Now</a>
        <a href="https://ldt4ssc.eu/faq/" class="btn btn-outline">Visit Helpdesk &amp; FAQ</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><div class="stat-val">€1M</div><div class="stat-lbl">Max / Consortium</div></div>
        <div class="stat"><div class="stat-val">50%</div><div class="stat-lbl">Co-funding</div></div>
        <div class="stat"><div class="stat-val">18 mo</div><div class="stat-lbl">Max Duration</div></div>
      </div>
    </div>
    <div class="hero-diagram">
      <svg viewBox="0 0 280 300" xmlns="http://www.w3.org/2000/svg">
        <circle cx="140" cy="135" r="128" fill="#D6E8F8" stroke="#B8D5F2" stroke-width="1"/>
        <circle cx="140" cy="135" r="102" fill="none" stroke="#B8D5F2" stroke-width="1" stroke-dasharray="4 7"/>
        <g stroke="#5497DC" stroke-width="1.5" opacity="0.5">
          <line x1="140" y1="135" x2="72"  y2="52"/><line x1="140" y1="135" x2="208" y2="52"/>
          <line x1="140" y1="135" x2="46"  y2="170"/><line x1="140" y1="135" x2="234" y2="170"/>
          <line x1="140" y1="135" x2="108" y2="232"/><line x1="140" y1="135" x2="172" y2="232"/>
          <line x1="72" y1="52" x2="208" y2="52" stroke="#5AB85A" stroke-width="1" opacity="0.5"/>
          <line x1="46" y1="170" x2="108" y2="232" stroke="#5AB85A" stroke-width="1" opacity="0.5"/>
          <line x1="234" y1="170" x2="172" y2="232" stroke="#5AB85A" stroke-width="1" opacity="0.5"/>
        </g>
        <circle cx="72"  cy="52"  r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/><text x="72"  y="57"  text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="208" cy="52"  r="18" fill="#EBF4FD" stroke="#1F75D6" stroke-width="2"/><text x="208" y="57"  text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#1F75D6">DT</text>
        <circle cx="46"  cy="170" r="18" fill="#EDF7E8" stroke="#29A329" stroke-width="2"/><text x="46"  y="175" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#29A329">DT</text>
        <circle cx="234" cy="170" r="18" fill="#EDF7E8" stroke="#29A329" stroke-width="2"/><text x="234" y="175" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#29A329">DT</text>
        <circle cx="108" cy="232" r="18" fill="#FFFAE8" stroke="#F5B400" stroke-width="2"/><text x="108" y="237" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#b07f00">AI</text>
        <circle cx="172" cy="232" r="18" fill="#FFFAE8" stroke="#F5B400" stroke-width="2"/><text x="172" y="237" text-anchor="middle" font-family="Arial" font-size="9" font-weight="700" fill="#b07f00">AI</text>
        <circle cx="140" cy="135" r="30" fill="#D6E8F8"/>
        <circle cx="140" cy="135" r="20" fill="#1F75D6" stroke="#fff" stroke-width="2.5"/>
        <text x="140" y="139" text-anchor="middle" font-family="Arial" font-size="10" font-weight="700" fill="#fff">EU</text>
        <g font-family="Arial" font-size="9.5" fill="#4C5562">
          <circle cx="12" cy="275" r="5" fill="#1F75D6"/><text x="21" y="279">Connect</text>
          <circle cx="12" cy="289" r="5" fill="#29A329"/><text x="21" y="293">Create</text>
          <circle cx="90" cy="275" r="5" fill="#F5B400"/><text x="99" y="279">AI Tools</text>
        </g>
      </svg>
    </div>
  </div>

  <div class="sec-label">Open Call 3</div>
  <h2 class="sec-title">What is Open Call 3?</h2>
  <p class="sec-sub">Open Call 3 covers all three Work Strands — interconnecting existing Local Digital Twins, creating new ones, and advancing AI-powered capabilities in the EU LDT Toolbox.</p>

  <div class="strands-grid">
    <div class="strand-intro si-blue">
      <div class="strand-num">01</div>
      <h3>Work Strand 1</h3>
      <p>Interconnecting existing Local Digital Twins for cross-border data exchange, shared services and interoperability.</p>
    </div>
    <div class="strand-intro si-green">
      <div class="strand-num">02</div>
      <h3>Work Strand 2</h3>
      <p>Creation of new Local Digital Twins based on shared challenges across cities and communities.</p>
    </div>
    <div class="strand-intro si-yellow">
      <div class="strand-num">03</div>
      <h3>Work Strand 3</h3>
      <p>Adding new and advanced AI services and innovative open-source components to the EU LDT Toolbox.</p>
    </div>
  </div>

  <div class="sec-divider"></div>

  <div class="block block-grey">
    <div class="sec-label">Benefits</div>
    <h2 class="sec-title">Why apply?</h2>
    <div class="why-grid">
      <div class="why-card">
        <div class="why-icon wi-blue">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#1F75D6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="9" cy="9" r="4"/><circle cx="17" cy="15" r="4"/><line x1="12.5" y1="11.5" x2="13.5" y2="13.5"/></svg>
        </div>
        <div class="why-body"><h3>01. Interconnect &amp; Build Digital Twins</h3><p>Connect existing LDTs or create new ones from the ground up to address shared urban and regional challenges across European communities.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-green">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#29A329" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 7V5a2 2 0 0 0-4 0v2"/><path d="M8 7V5a2 2 0 0 0-4 0v2"/><line x1="12" y1="12" x2="12" y2="16"/><line x1="10" y1="14" x2="14" y2="14"/></svg>
        </div>
        <div class="why-body"><h3>02. Secure Financial Support</h3><p>Access substantial EU funding through the Digital Europe Programme to de-risk innovation and pilot new solutions at up to €1M per consortium.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-yellow">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#b07f00" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="7" height="7" rx="1"/><rect x="14" y="3" width="7" height="7" rx="1"/><rect x="3" y="14" width="7" height="7" rx="1"/><path d="M17.5 14v3m0 3v.01M14 17.5h3m3 0h.01"/></svg>
        </div>
        <div class="why-body"><h3>03. Access the EU LDT Toolbox</h3><p>Build on open-source specifications and tools developed within the LDT4SSC project ecosystem.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-blue">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#1F75D6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2a4 4 0 0 1 4 4c0 1.5-.8 2.8-2 3.5V12l3 3-3 1v2l-2-1-2 1v-2l-3-1 3-3V9.5A4 4 0 0 1 8 6a4 4 0 0 1 4-4z"/><path d="M9 18c-2 .5-4 1.5-4 3h14c0-1.5-2-2.5-4-3"/></svg>
        </div>
        <div class="why-body"><h3>04. Advance AI Capabilities</h3><p>Contribute cutting-edge AI services that simulate future scenarios and enhance decision-making for smart communities.</p></div>
      </div>
    </div>
  </div>

  <div class="block block-blue">
    <div class="sec-label">Key Dates</div>
    <h2 class="sec-title">What to remember?</h2>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">13 May 2026</div>
        <div class="tl-title">Launch</div>
        <div class="tl-desc">Applications open and all documents available for download</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">13 July 2026 · 23:59 CEST</div>
        <div class="tl-title">Deadline</div>
        <div class="tl-desc">All applications must be submitted to applications@ldt4ssc.eu</div>
      </div>
      <div class="tl-item tl-upcoming">
        <div class="tl-dot"></div>
        <div class="tl-date">TBC</div>
        <div class="tl-title">Pilot start</div>
        <div class="tl-desc">Selected consortia begin their implementation phase</div>
      </div>
    </div>
  </div>

  <div class="sec-divider"></div>

  <div class="sec-label">Application Documents</div>
  <h2 class="sec-title">Download Application Documents</h2>
  <p class="sec-sub">Ensure all documents are completed, signed, eligibility criteria met and alignment with your chosen Work Strand objectives.</p>

  <div class="doc-strand ds-blue">
    <div class="doc-strand-label">Work Strand 01</div>
    <h3>Interconnecting Existing Local Digital Twins</h3>
    <div class="doc-buttons">
      <a href="/documents/ws1callforpilotsmanual.pdf" class="doc-btn">Pilot Manual</a>
      <a href="/documents/ws1applicationform.docx" class="doc-btn">Application Form</a>
      <a href="/documents/ws1letterofcommitment.docx" class="doc-btn">Letter of Commitment</a>
      <a href="/documents/ws1ownershipcontroldeclaration.docx" class="doc-btn">Ownership Declaration</a>
      <a href="/documents/ws1financialform.xlsx" class="doc-btn">Financial Form</a>
      <a href="/documents/ws1ethicsanddataprotectionwork.xlsx" class="doc-btn">Ethics Assessment</a>
    </div>
  </div>

  <div class="doc-strand ds-green">
    <div class="doc-strand-label">Work Strand 02</div>
    <h3>Creating New Local Digital Twins Based on Common Needs</h3>
    <div class="doc-buttons">
      <a href="/documents/ws2callforpilotsmanual.pdf" class="doc-btn">Pilot Manual</a>
      <a href="/documents/ws2applicationform.docx" class="doc-btn">Application Form</a>
      <a href="/documents/ws2letterofcommitment.docx" class="doc-btn">Letter of Commitment</a>
      <a href="/documents/ws2letterofintent.docx" class="doc-btn">Letter of Intent</a>
      <a href="/documents/ws2ownershipcontroldeclaration.docx" class="doc-btn">Ownership Declaration</a>
      <a href="/documents/ws2financialform.xlsx" class="doc-btn">Financial Form</a>
      <a href="/documents/ws2ethicsanddataprotectionwork.xlsx" class="doc-btn">Ethics Assessment</a>
    </div>
  </div>

  <div class="doc-strand ds-yellow">
    <div class="doc-strand-label">Work Strand 03</div>
    <h3>Adding New Advanced AI-Based Capabilities to the LDT Toolbox</h3>
    <div class="doc-buttons">
      <a href="/documents/ws3callforpilotsmanual.pdf" class="doc-btn">Pilot Manual</a>
      <a href="/documents/ws3applicationform.docx" class="doc-btn">Application Form</a>
      <a href="/documents/ws3letterofcommitment.docx" class="doc-btn">Letter of Commitment</a>
      <a href="/documents/ws3ownershipcontroldeclaration.docx" class="doc-btn">Ownership Declaration</a>
      <a href="/documents/ws3financialform.xlsx" class="doc-btn">Financial Form</a>
      <a href="/documents/ws3ethicsanddataprotectionwork.xlsx" class="doc-btn">Ethics Assessment</a>
    </div>
  </div>

  <div class="doc-strand ds-grey">
    <div class="doc-strand-label">Additional Document</div>
    <h3>LDT4SSC Guarantee Form</h3>
    <p class="doc-note">Required for applicants from non-EU/EEA countries participating under the Digital Europe Programme. Organisations based in EU or EEA member states do not need to submit this form.</p>
    <div class="doc-buttons">
      <a href="https://ldt4ssc.eu/documents/LDT4SSC-guarantee.docx" class="doc-btn">Download Guarantee Form</a>
    </div>
  </div>

  <div class="sec-divider"></div>

  <div class="block block-grey" style="margin-bottom: 32px;">
    <div class="info-inner">
      <div>
        <div class="sec-label" style="margin-bottom:8px;">Resources</div>
        <h2 class="sec-title">Open Call 3 – Info Session</h2>
        <p style="font-size:14px; color:var(--grey-mid); line-height:1.7; margin-bottom:22px;">The Open Call 3 Info Session was held on <strong>22 May 2026</strong>. The recording and presentation slides are available below.</p>
        <div style="display:flex; gap:12px; flex-wrap:wrap; margin-bottom:22px;">
          <a href="https://youtu.be/QBZLbNLpuII" class="btn btn-blue" target="_blank">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8" fill="currentColor" stroke="none"/></svg>
            Watch Recording
          </a>
          <a href="https://ldt4ssc.eu/documents/info-session-three.pdf" class="btn btn-outline" target="_blank">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/></svg>
            Download Slides
          </a>
        </div>
        <a href="https://shorturl.at/pzMGK" class="btn btn-outline" style="font-size:13px;">Subscribe for Updates</a>
      </div>
      <div class="glance">
        <div class="glance-head">Call at a glance</div>
        <div class="glance-row"><span class="gr-key">Status</span><span class="gr-val gr-open">&#9679; Open</span></div>
        <div class="glance-row"><span class="gr-key">Programme</span><span class="gr-val">Digital Europe (DEP)</span></div>
        <div class="glance-row"><span class="gr-key">Work Strands</span><span class="gr-val">WS 1, WS 2 &amp; WS 3</span></div>
        <div class="glance-row"><span class="gr-key">Max per consortium</span><span class="gr-val">€1,000,000</span></div>
        <div class="glance-row"><span class="gr-key">Co-funding required</span><span class="gr-val">50%</span></div>
        <div class="glance-row"><span class="gr-key">Launch date</span><span class="gr-val">13 May 2026</span></div>
        <div class="glance-row"><span class="gr-key">Submission deadline</span><span class="gr-val">13 Jul 2026</span></div>
      </div>
    </div>
  </div>

  <div class="sec-label">Get Involved</div>
  <div class="cta-grid">
    <div class="cta-card cta-card-blue">
      <h3>Find Partners</h3>
      <p>Connect with potential consortium partners from across Europe via the LDT4SSC Matchmaking Platform.</p>
      <div class="cta-links">
        <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="cta-link">Matchmaking Platform</a>
      </div>
    </div>
    <div class="cta-card cta-card-green">
      <h3>Stay Informed</h3>
      <p>Subscribe to the newsletter to receive updates on the call, info sessions and project news.</p>
      <div class="cta-links">
        <a href="https://shorturl.at/pzMGK" class="cta-link">Subscribe to Newsletter</a>
      </div>
    </div>
    <div class="cta-card cta-card-yellow">
      <h3>Join the Community</h3>
      <p>Become part of the stakeholder forum shaping Europe's digital twin ecosystem.</p>
      <div class="cta-links">
        <a href="https://forms.gle/v17Y7df5DUwpCRZP6" class="cta-link">Join Stakeholder Forum</a>
        <a href="https://ldt4ssc.eu/faq/" class="cta-link">Helpdesk &amp; FAQ</a>
      </div>
    </div>
  </div>

</div>
