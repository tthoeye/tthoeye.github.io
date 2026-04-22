---
layout: fullwidth
permalink: /call-three/
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
  background: var(--blue-tint);
  color: var(--ink);
  text-align: center;
  padding: 11px 20px;
  font-size: 13.5px;
  font-weight: 700;
  border-radius: 8px;
  margin-bottom: 28px;
  border: 2px solid var(--blue-pale);
}

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
.oc2 .hero-badge { display: inline-flex; align-items: center; gap: 8px; background: var(--blue-pale); border: 1.5px solid var(--blue-mid); color: var(--blue); font-size: 12px; font-weight: 700; letter-spacing: 0.07em; text-transform: uppercase; padding: 5px 12px; border-radius: 100px; margin-bottom: 18px; }
.oc2 .hero-badge .dot { width: 7px; height: 7px; background: var(--blue); border-radius: 50%; }
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
.oc2 .two-col      { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 24px; }
.oc2 .cta-grid     { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
.oc2 .info-inner   { display: grid; grid-template-columns: 1fr 1fr; gap: 32px; align-items: start; }

.oc2 .strand-intro { background: #fff; border: 1.5px solid var(--grey-pale); border-top: 4px solid var(--blue); border-radius: 10px; padding: 28px 24px; transition: box-shadow 0.2s; }
.oc2 .strand-intro:hover { box-shadow: 0 6px 20px rgba(31,117,214,0.10); }
.oc2 .strand-num { font-size: 40px; font-weight: 700; color: var(--blue-pale); line-height: 1; margin-bottom: 8px; }
.oc2 .strand-intro h3 { font-size: 16px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .strand-intro p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); }
.oc2 .block-blue { background: var(--blue-tint); border: 1.5px solid var(--blue-pale); }

.oc2 .why-card { background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 10px; padding: 24px; display: flex; gap: 16px; align-items: flex-start; transition: border-color 0.2s, box-shadow 0.2s; }
.oc2 .why-card:hover { border-color: var(--blue-mid); box-shadow: 0 4px 16px rgba(31,117,214,0.09); }
.oc2 .why-icon { width: 42px; height: 42px; border-radius: 10px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
.oc2 .wi-blue   { background: var(--blue-tint); }
.oc2 .wi-green  { background: var(--green-tint); }
.oc2 .wi-yellow { background: var(--yellow-tint); }
.oc2 .wi-grey   { background: var(--grey-pale); }
.oc2 .why-body h3 { font-size: 15px !important; font-weight: 700; color: var(--ink); margin-bottom: 5px !important; }
.oc2 .why-body p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

.oc2 .who-card { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); border-radius: 12px; padding: 36px; }
.oc2 .who-card h3 { font-size: 17px !important; font-weight: 700; color: var(--ink); margin-bottom: 20px !important; }
.oc2 .who-tags { display: flex; flex-wrap: wrap; gap: 9px; }
.oc2 .who-tag { background: #fff; border: 1.5px solid var(--grey-pale); color: var(--grey); font-size: 13px; font-weight: 700; padding: 6px 13px; border-radius: 100px; }

.oc2 .coming-soon-card {
  background: var(--blue);
  border-radius: 14px;
  padding: 56px 48px;
  text-align: center;
  color: #fff;
  margin-bottom: 24px;
}
.oc2 .coming-soon-card h2 { font-size: clamp(22px, 2.5vw, 30px) !important; font-weight: 700; color: #fff !important; margin-bottom: 12px !important; }
.oc2 .coming-soon-card p { font-size: 15px; opacity: 0.8; line-height: 1.7; max-width: 560px; margin: 0 auto 28px; }
.oc2 .coming-soon-card .cs-badge { display: inline-flex; align-items: center; gap: 8px; background: rgba(255,255,255,0.15); border: 1.5px solid rgba(255,255,255,0.3); color: #fff; font-size: 13px; font-weight: 700; letter-spacing: 0.07em; text-transform: uppercase; padding: 8px 18px; border-radius: 100px; margin-bottom: 28px; }

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
.oc2 .gr-open     { color: var(--green) !important; }
.oc2 .gr-upcoming { color: var(--blue) !important; }

.oc2 .contact-card { background: var(--blue-tint); border: 1.5px solid var(--blue-pale); border-radius: 12px; padding: 36px; }
.oc2 .contact-card h3 { font-size: 18px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .contact-card p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 22px; }
.oc2 .cta-links { display: flex; flex-direction: column; gap: 9px; }
.oc2 .cta-link { display: flex; align-items: center; gap: 11px; padding: 11px 14px; background: #fff; border: 1.5px solid var(--blue-pale); border-radius: 8px; font-size: 13.5px; font-weight: 700; color: var(--blue) !important; transition: border-color 0.15s, background 0.15s; }
.oc2 .cta-link:hover { border-color: var(--blue); background: var(--blue-pale); }
.oc2 .eval-card { background: var(--yellow-tint); border: 1.5px solid var(--yellow-pale); border-radius: 12px; padding: 36px; display: flex; flex-direction: column; }
.oc2 .eval-card h3 { font-size: 18px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .eval-card p  { font-size: 14px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 26px; flex: 1; }

.oc2 .prev-call-card {
  background: var(--grey-tint);
  border: 1.5px solid var(--grey-pale);
  border-radius: 12px;
  padding: 28px 32px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  margin-bottom: 24px;
  flex-wrap: wrap;
}
.oc2 .prev-call-card p { font-size: 13.5px; color: var(--grey-mid); margin-top: 4px; }
.oc2 .prev-call-card h4 { font-size: 15px; font-weight: 700; color: var(--ink); }

@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .hero { grid-template-columns: 1fr; padding: 28px; }
  .oc2 .hero-diagram { display: none; }
  .oc2 .strands-grid, .oc2 .why-grid, .oc2 .two-col,
  .oc2 .timeline, .oc2 .cta-grid, .oc2 .info-inner { grid-template-columns: 1fr; }
  .oc2 .timeline::before { display: none; }
  .oc2 .tl-item { padding-top: 0; padding-left: 24px; padding-bottom: 20px; }
  .oc2 .tl-dot  { top: 2px; left: 0; }
  .oc2 .block   { padding: 24px; }
  .oc2 .coming-soon-card { padding: 36px 24px; }
  .oc2 .contact-card, .oc2 .eval-card { padding: 24px; }
  .oc2 .prev-call-card { flex-direction: column; align-items: flex-start; }
}
</style>

<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <div class="banner">
    Open Call 3 launches on <strong>13 May 2026</strong> — More information coming soon
  </div>

  <div class="hero">
    <div>
      <div class="hero-badge"><span class="dot"></span> Open Call 3 · Status: Upcoming</div>
      <h1>Third Round of <span class="accent">Open Calls</span></h1>
      <p class="hero-sub">The Local Digital Twins for Smart and Sustainable Communities (LDT4SSC) project, funded by the Digital Europe Programme (DEP), will invite applications for its third Open Call focused on creating and enhancing Local Digital Twins across Europe.</p>
      <div class="hero-btns">
        <a href="https://shorturl.at/pzMGK" class="btn btn-blue">Subscribe for Updates</a>
        <a href="https://ldt4ssc.eu/faq/" class="btn btn-outline">Visit Helpdesk &amp; FAQ</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><div class="stat-val">WS 1</div><div class="stat-lbl">Work Strand 1</div></div>
        <div class="stat"><div class="stat-val">WS 2</div><div class="stat-lbl">Work Strand 2</div></div>
        <div class="stat"><div class="stat-val">WS 3</div><div class="stat-lbl">Work Strand 3</div></div>
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
    <div class="strand-intro">
      <div class="strand-num">01</div>
      <h3>Work Strand 1</h3>
      <p>Interconnecting existing Local Digital Twins for cross-border data exchange, shared services and interoperability.</p>
    </div>
    <div class="strand-intro">
      <div class="strand-num">02</div>
      <h3>Work Strand 2</h3>
      <p>Creation of new Local Digital Twins based on shared challenges across cities and communities.</p>
    </div>
    <div class="strand-intro">
      <div class="strand-num">03</div>
      <h3>Work Strand 3</h3>
      <p>Adding new and advanced AI services and innovative open-source components to the EU LDT Toolbox.</p>
    </div>
  </div>

  <div class="sec-divider"></div>

  <div class="coming-soon-card">
    <div class="cs-badge">Launching 13 May 2026</div>
    <h2>Full details coming soon</h2>
    <p style="color:#fff;">Eligibility criteria, funding amounts, and submission guidelines will be published at launch on 13 May 2026. Subscribe to be notified the moment the call opens.</p>
    <a href="https://shorturl.at/pzMGK" class="btn btn-yellow">Subscribe for Updates</a>
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
        <div class="why-icon wi-yellow">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#b07f00" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 7V5a2 2 0 0 0-4 0v2"/><path d="M8 7V5a2 2 0 0 0-4 0v2"/><line x1="12" y1="12" x2="12" y2="16"/><line x1="10" y1="14" x2="14" y2="14"/></svg>
        </div>
        <div class="why-body"><h3>02. Secure Financial Support</h3><p>Access substantial EU funding through the Digital Europe Programme to de-risk innovation and pilot new solutions.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-green">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#29A329" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="7" height="7" rx="1"/><rect x="14" y="3" width="7" height="7" rx="1"/><rect x="3" y="14" width="7" height="7" rx="1"/><path d="M17.5 14v3m0 3v.01M14 17.5h3m3 0h.01"/></svg>
        </div>
        <div class="why-body"><h3>03. Access the EU LDT Toolbox</h3><p>Build on open-source specifications and tools developed within the LDT4SSC project ecosystem.</p></div>
      </div>
      <div class="why-card">
        <div class="why-icon wi-grey">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#4C5562" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2a4 4 0 0 1 4 4c0 1.5-.8 2.8-2 3.5V12l3 3-3 1v2l-2-1-2 1v-2l-3-1 3-3V9.5A4 4 0 0 1 8 6a4 4 0 0 1 4-4z"/><path d="M9 18c-2 .5-4 1.5-4 3h14c0-1.5-2-2.5-4-3"/></svg>
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
        <div class="tl-desc">Applications open and all documents become available</div>
      </div>
      <div class="tl-item">
        <div class="tl-dot"></div>
        <div class="tl-date">13 July 2026 · 23:59 CEST</div>
        <div class="tl-title">Deadline</div>
        <div class="tl-desc">All applications must be submitted by this date</div>
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

  <div class="block block-grey" style="margin-bottom:24px;">
    <div class="info-inner">
      <div class="info-left">
        <div class="sec-label" style="margin-bottom:8px;">Resources</div>
        <h2>Open Call 3 – Info Session</h2>
        <p>An information session will be held ahead of the launch on 13 May 2026. Slides and recording will be made available here once published.</p>
        <div class="info-btns" style="margin-top:22px;">
          <a href="https://shorturl.at/pzMGK" class="btn btn-blue">Subscribe for Updates</a>
        </div>
      </div>
      <div class="glance">
        <div class="glance-head">Call at a glance</div>
        <div class="glance-row"><span class="gr-key">Status</span><span class="gr-val gr-upcoming">● Upcoming</span></div>
        <div class="glance-row"><span class="gr-key">Programme</span><span class="gr-val">Digital Europe (DEP)</span></div>
        <div class="glance-row"><span class="gr-key">Work Strands</span><span class="gr-val">WS 1, WS 2 &amp; WS 3</span></div>
        <div class="glance-row"><span class="gr-key">Max per consortium</span><span class="gr-val">TBC at launch</span></div>
        <div class="glance-row"><span class="gr-key">Launch date</span><span class="gr-val">13 May 2026</span></div>
        <div class="glance-row"><span class="gr-key">Submission deadline</span><span class="gr-val">13 Jul 2026</span></div>
      </div>
    </div>
  </div>

</div>
