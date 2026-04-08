---
title: News & Events
layout: fullwidth
description: The Local Digital Twins for Smart Communities project (LDT4SSC) supports European communities in developing, connecting and advancing Local Digital Twins for AI supported decision making
intro_image_absolute: false
intro_image_hide_on_mobile: true
show_call_box: true
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
.oc2 .sec-label.green { color: var(--green); }
.oc2 .sec-label.green::before { background: var(--green); }
.oc2 .sec-label.yellow { color: #9a7300; }
.oc2 .sec-label.yellow::before { background: var(--yellow); }

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
  margin: 8px 0 40px;
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
  margin-bottom: 14px !important;
  border: none !important;
  padding: 0 !important;
}
.oc2 .page-hero h1 .accent { color: var(--blue); }
.oc2 .page-hero h1 .accent-green { color: var(--green); }
.oc2 .page-hero-sub {
  font-size: 16px;
  color: var(--grey);
  line-height: 1.7;
  max-width: 700px;
  margin: 0 auto;
}

/* ── CARDS GRID ── */
.oc2 .cards-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-bottom: 48px;
}

/* ── NEWS CARD ── */
.oc2 .news-card {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-top: 4px solid var(--blue);
  border-radius: 10px;
  padding: 24px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  transition: box-shadow 0.2s, border-color 0.2s;
  text-decoration: none;
}
.oc2 .news-card:hover {
  box-shadow: 0 6px 20px rgba(31,117,214,0.10);
  border-color: var(--blue-pale);
}
.oc2 .news-card .card-date {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  color: var(--blue);
}
.oc2 .news-card .card-title {
  font-size: 14.5px;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.4;
  flex: 1;
}
.oc2 .news-card .card-excerpt {
  font-size: 13px;
  color: var(--grey-mid);
  line-height: 1.65;
}
.oc2 .news-card .card-more {
  font-size: 12.5px;
  font-weight: 700;
  color: var(--blue);
  margin-top: 4px;
}

/* ── EVENT CARD ── */
.oc2 .event-card {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-top: 4px solid var(--green);
  border-radius: 10px;
  padding: 24px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  transition: box-shadow 0.2s, border-color 0.2s;
  text-decoration: none;
}
.oc2 .event-card:hover {
  box-shadow: 0 6px 20px rgba(41,163,41,0.10);
  border-color: var(--green-pale);
}
.oc2 .event-card .card-date {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  color: var(--green);
  display: flex;
  align-items: center;
  gap: 6px;
}
.oc2 .event-card .card-title {
  font-size: 14.5px;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.4;
  flex: 1;
}
.oc2 .event-card .card-excerpt {
  font-size: 13px;
  color: var(--grey-mid);
  line-height: 1.65;
}
.oc2 .event-card .card-more {
  font-size: 12.5px;
  font-weight: 700;
  color: var(--green);
  margin-top: 4px;
}

/* ── RESOURCE CARD (recordings, materials) ── */
.oc2 .resource-card {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-top: 4px solid var(--yellow);
  border-radius: 10px;
  padding: 24px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  transition: box-shadow 0.2s, border-color 0.2s;
  text-decoration: none;
}
.oc2 .resource-card:hover {
  box-shadow: 0 6px 20px rgba(245,180,0,0.13);
  border-color: var(--yellow-pale);
}
.oc2 .resource-card .card-date {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  color: #9a7300;
  display: flex;
  align-items: center;
  gap: 6px;
}
.oc2 .resource-card .card-title {
  font-size: 14.5px;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.4;
  flex: 1;
}
.oc2 .resource-card .card-excerpt {
  font-size: 13px;
  color: var(--grey-mid);
  line-height: 1.65;
}
.oc2 .resource-card .card-more {
  font-size: 12.5px;
  font-weight: 700;
  color: #9a7300;
  margin-top: 4px;
}

/* ── YELLOW HIGHLIGHT BAND ── */
.oc2 .highlight-band {
  background: var(--yellow);
  border-radius: 10px;
  padding: 18px 28px;
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 40px;
  font-size: 14px;
  font-weight: 700;
  color: var(--ink);
}
.oc2 .highlight-band a {
  color: var(--ink);
  text-decoration: underline;
}
@media (max-width: 900px) {
  .oc2 .cards-grid { grid-template-columns: repeat(2, 1fr); }
}
@media (max-width: 600px) {
  .oc2 { padding: 0 16px; }
  .oc2 .page-hero { padding: 28px 20px; }
  .oc2 .cards-grid { grid-template-columns: 1fr; }
}
</style>

<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <!-- HERO -->
  <div class="page-hero">
    <div class="sec-label" style="justify-content:center;">LDT4SSC</div>
    <h1><span class="accent">News</span> &amp; <span class="accent-green">Events</span></h1>
    <p class="page-hero-sub">Welcome to the LDT4SSC hub! Here you'll find the latest news, project updates, events and community highlights. Follow our progress as we build a European network of interoperable Local Digital Twins, showcase pilot innovations and share ways to get involved.</p>
  </div>

  <!-- EVENTS -->
  <div class="sec-label green">Upcoming &amp; Recent Events</div>
  <h2 class="sec-title">Events</h2>
  <p class="sec-sub">Webinars, forums, matchmaking sessions and conferences featuring the LDT4SSC project.</p>

  <div class="cards-grid">
    {% assign events = site.services | where: "type", "event" | sort: "date" | reverse | limit: 6 %}
    {% for item in events %}
    <a href="{{ item.url }}" class="event-card">
      <div class="card-date">{{ item.date | date: "%d %B %Y" }}</div>
      <div class="card-title">{{ item.title }}</div>
      {% if item.excerpt %}
      <div class="card-excerpt">{{ item.excerpt | strip_html | truncatewords: 20 }}</div>
      {% endif %}
      <div class="card-more">Learn more →</div>
    </a>
    {% endfor %}
  </div>

  <div class="sec-divider"></div>

  <!-- NEWS -->
  <div class="sec-label">Latest News</div>
  <h2 class="sec-title">News</h2>
  <p class="sec-sub">Project updates and announcements from across the LDT4SSC initiative.</p>

  <div class="cards-grid">
    {% assign news = site.services | where: "type", "news" | sort: "date" | reverse | limit: 6 %}
    {% for item in news %}
    <a href="{{ item.url }}" class="news-card">
      <div class="card-date">{{ item.date | date: "%d %B %Y" }}</div>
      <div class="card-title">{{ item.title }}</div>
      {% if item.excerpt %}
      <div class="card-excerpt">{{ item.excerpt | strip_html | truncatewords: 20 }}</div>
      {% endif %}
      <div class="card-more">Read more →</div>
    </a>
    {% endfor %}
  </div>

</div>
