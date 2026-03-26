---
title: Contact
layout: fullwidth
description: Contact Us
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

/* CSS variables — brand palette only */
.oc2 {
  --blue:        #1F75D6;
  --blue-mid:    #5497DC;
  --blue-pale:   #C8DFF5;
  --blue-tint:   #EBF4FD;
  --green:       #29A329;
  --green-pale:  #C8E8C8;
  --green-tint:  #EDF7E8;
  --yellow:      #F5B400;
  --yellow-pale: #F5D980;
  --yellow-tint: #FEF7DC;
  --grey:        #4C5562;
  --grey-mid:    #7A8494;
  --grey-pale:   #D8DCE3;
  --grey-tint:   #F2F3F5;
  --ink:         #4C5562;
}

/* ── BUTTONS ── */
.oc2 .btn {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  padding: 11px 20px;
  border-radius: 6px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 14px;
  font-weight: 700;
  transition: filter 0.15s, transform 0.15s;
  cursor: pointer;
  line-height: 1;
}
.oc2 .btn:hover { filter: brightness(1.08); transform: translateY(-1px); }
.oc2 .btn-blue   { background: var(--blue);   color: #fff !important; }
.oc2 .btn-green  { background: var(--green);  color: #fff !important; }
.oc2 .btn-yellow { background: var(--yellow); color: var(--ink) !important; }
.oc2 .btn-outline {
  background: #fff;
  border: 2px solid var(--blue);
  color: var(--blue) !important;
}
.oc2 .btn-outline:hover { background: var(--blue-tint); filter: none; }

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

/* ── HERO ── */
.oc2 .hero {
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-radius: 14px;
  padding: 48px;
  margin-bottom: 40px;
}
.oc2 .hero h1 {
  font-family: Arial, Helvetica, sans-serif !important;
  font-size: clamp(26px, 3vw, 44px) !important;
  font-weight: 700 !important;
  color: var(--ink) !important;
  line-height: 1.1 !important;
  margin-bottom: 16px !important;
  border: none !important;
  padding: 0 !important;
}
.oc2 .hero h1 .accent { color: var(--blue); }
.oc2 .hero-sub {
  font-size: 15px;
  color: var(--grey);
  line-height: 1.7;
  margin-bottom: 28px;
  max-width: 680px;
}
.oc2 .hero-btns { display: flex; gap: 12px; flex-wrap: wrap; }

/* ── BLOCK ── */
.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); }
.oc2 .block-blue { background: var(--blue-tint); border: 1.5px solid var(--blue-pale); }

/* ── CONTACT GRID ── */
.oc2 .contact-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-bottom: 24px;
}

/* ── CHANNEL CARDS ── */
.oc2 .channel-card {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-radius: 12px;
  padding: 32px;
  display: flex;
  flex-direction: column;
  gap: 0;
  transition: border-color 0.2s, box-shadow 0.2s;
}
.oc2 .channel-card:hover { border-color: var(--blue-mid); box-shadow: 0 4px 18px rgba(31,117,214,0.09); }
.oc2 .channel-icon {
  width: 48px; height: 48px;
  border-radius: 12px;
  display: flex; align-items: center; justify-content: center;
  font-size: 22px;
  margin-bottom: 16px;
  flex-shrink: 0;
}
.oc2 .ci-blue   { background: var(--blue-tint); }
.oc2 .ci-green  { background: var(--green-tint); }
.oc2 .ci-yellow { background: var(--yellow-tint); }
.oc2 .channel-card h3 {
  font-size: 17px !important;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 8px !important;
}
.oc2 .channel-card p {
  font-size: 13.5px;
  color: var(--grey-mid);
  line-height: 1.7;
  margin-bottom: 20px;
  flex: 1;
}
.oc2 .channel-link {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 10px 16px;
  border-radius: 6px;
  font-size: 13.5px;
  font-weight: 700;
  transition: filter 0.15s, transform 0.15s;
  align-self: flex-start;
}
.oc2 .channel-link:hover { filter: brightness(1.08); transform: translateY(-1px); }
.oc2 .cl-blue   { background: var(--blue);   color: #fff !important; }
.oc2 .cl-green  { background: var(--green);  color: #fff !important; }
.oc2 .cl-yellow { background: var(--yellow); color: var(--ink) !important; }

/* ── CTA LINKS (wide card) ── */
.oc2 .cta-links { display: flex; flex-direction: column; gap: 9px; }
.oc2 .cta-link {
  display: flex; align-items: center; gap: 11px;
  padding: 11px 14px; background: #fff;
  border: 1.5px solid var(--blue-pale); border-radius: 8px;
  font-size: 13.5px; font-weight: 700; color: var(--blue) !important;
  transition: border-color 0.15s, background 0.15s;
}
.oc2 .cta-link:hover { border-color: var(--blue); background: var(--blue-pale); }


/* ── RESPONSIVE ── */
@media (max-width: 768px) {
  .oc2 .contact-grid { grid-template-columns: 1fr; }
  .oc2 .hero { padding: 28px; }
  .oc2 .block { padding: 24px; }
  .oc2 { padding: 0 16px; }
}
</style>

<div class="oc2-escape">
<div class="oc2">

  <!-- HERO -->
  <div class="hero">
    <div class="sec-label">Contact</div>
    <h1>Get in <span class="accent">Touch</span></h1>
    <p class="hero-sub">Got a question or want to connect with the LDT4SSC team? Use our contact form, follow our updates on LinkedIn or subscribe to our newsletter.</p>
    <div class="hero-btns">
      <a href="/faq/#contact-form" class="btn btn-blue">📋 Contact Form</a>
      <a href="https://www.linkedin.com/company/ldt4ssc-project/" target="_blank" class="btn btn-green">in Follow on LinkedIn</a>
      <a href="https://shorturl.at/pzMGK" target="_blank" class="btn btn-yellow">📬 Subscribe to Newsletter</a>
    </div>
  </div>

  <!-- CONTACT CHANNELS -->
  <div class="sec-label">Channels</div>
  <h2 class="sec-title">How to reach us</h2>
  <p class="sec-sub">Choose the channel that works best for you — we're happy to help with questions about the open call, events or the project in general.</p>

  <div class="contact-grid">
    <div class="channel-card">
      <div class="channel-icon ci-blue">📋</div>
      <h3>Contact Form</h3>
      <p>The easiest way to get in touch — use the contact form at the bottom of the FAQ page for questions, feedback or any other enquiries.</p>
      <a href="/faq/" class="channel-link cl-blue">Go to FAQ page →</a>
    </div>
    <div class="channel-card">
      <div class="channel-icon ci-green">in</div>
      <h3>Follow on LinkedIn</h3>
      <p>Stay up to date with project news, event announcements, and open call updates on our LinkedIn page.</p>
      <a href="https://www.linkedin.com/company/ldt4ssc-project/" target="_blank" class="channel-link cl-green">Follow LDT4SSC →</a>
    </div>
    <div class="channel-card">
      <div class="channel-icon ci-yellow">📬</div>
      <h3>Newsletter</h3>
      <p>Subscribe to the LDT4SSC newsletter to receive updates on open calls, events and news from the European digital twin ecosystem directly in your inbox.</p>
      <a href="https://shorturl.at/pzMGK" target="_blank" class="channel-link cl-yellow">Subscribe now →</a>
    </div>
  </div>

</div>
</div>
