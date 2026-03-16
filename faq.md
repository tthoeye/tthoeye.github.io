---
title: FAQ
layout: faq
description: Frequently Asked Questions
permalink: /faq/
intro_image_absolute: false
intro_image_hide_on_mobile: true
---
# FAQ

Find answers to the most common questions about the LDT4SSC project, the Knowledge Hub, and how to get in touch with the team.

<!-- Full-Width Project Intro and FAQ -->
<section class="ldt4ssc-intro full-width">
  <div class="intro-container">
    <h2>About the LDT4SSC Project</h2>
    <p><strong>Local Digital Twins for Smart and Sustainable Communities (LDT4SSC)</strong> is a European project supporting cities, regions and public authorities in the development, interconnection and enhancement of Local Digital Twins (LDTs). The project builds a federated, interoperable and reusable European ecosystem of LDTs, aligned with common standards, data spaces and the SIMPL framework. Funding and technical support are provided via Open Calls for Pilots.</p>

    <h3>LDT4SSC Work Strands</h3>
    <div class="work-strands">
      <div class="ws-card">
        <h4>WS1 – Interconnecting Existing Local Digital Twins</h4>
        <p>Connects operational LDTs for cross-border data exchange, shared services and interoperability.</p>
      </div>
      <div class="ws-card">
        <h4>WS2 – Creating New Local Digital Twins Based on Common Needs</h4>
        <p>Co-design and deploy new LDTs addressing shared urban challenges.</p>
      </div>
      <div class="ws-card">
        <h4>WS3 – Adding Advanced AI-Based Capabilities to LDTs</h4>
        <p>Develops advanced AI-driven predictive and immersive services on LDTs.</p>
      </div>
    </div>

    <h3>Useful Documents & Links</h3>
    <ul class="resources">
      <li><a href="https://ldt4ssc.eu/open-calls/">LDT4SSC Open Calls pages</a></li>
      <li><a href="https://ldt4ssc.eu/call-for-pilots-manual.pdf">Call for Pilots Manual</a></li>
      <li><a href="https://ldt4ssc.eu/application-forms/">Application forms and templates per Work Strand</a></li>
      <li><a href="https://ldt4ssc.eu/matchmaking-platform/">Matchmaking Platform</a></li>
      <li><a href="https://ldt4ssc.eu/news/">News & Events page</a></li>
    </ul>
  </div>
</section>


<section class="faq-accordion full-width">
  <!-- FAQ 1 -->
  <details>
    <summary>1</summary>
    <div class="faq-content">
      <p><strong>Q1:</strong> Where can I find official information on call timelines, requirements and eligibility?</p>
      <p><strong>A1:</strong> All official information is provided in the Call for Pilots Manual on the LDT4SSC website.</p>
      <hr>
      <p><strong>Q2:</strong> When will details on upcoming calls be published?</p>
      <p><strong>A2:</strong> Updates for WS2 and WS3 will be published closer to their launch dates.</p>
      <hr>
      <p><strong>Q3:</strong> What is question three for title 1?</p>
      <p><strong>A3:</strong> Answer to question three under title 1.</p>
    </div>
  </details>

  <!-- Repeat FAQ 2–7 blocks similarly -->
</section>

<style>
.full-width {
  width: 100%;
  padding: 40px 60px; /* Full width with comfortable padding */
  box-sizing: border-box;
}

.intro-container {
  max-width: none; /* Span entire page */
}

.ldt4ssc-intro h2 {
  color: #1F75D6;
  font-size: 32px;
  margin-bottom: 20px;
}

.ldt4ssc-intro h3 {
  color: #29A329;
  margin-top: 30px;
  margin-bottom: 15px;
  font-size: 24px;
}

.ldt4ssc-intro p {
  color: #4C5562;
  line-height: 1.7;
  margin-bottom: 18px;
}

.work-strands {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: space-between; /* Spread cards across full width */
}

.ws-card {
  flex: 1 1 28%;
  background: #ffffff;
  border-left: 5px solid #F5B400;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.08);
  min-width: 250px;
}

.ws-card h4 {
  margin-top: 0;
  margin-bottom: 10px;
  color: #1F75D6;
}

.resources li {
  margin-bottom: 10px;
}

.resources a {
  color: #1F75D6;
  text-decoration: none;
  font-weight: 500;
}

.resources a:hover {
  text-decoration: underline;
}

/* FAQ Accordion */
.faq-accordion details {
  border: 1px solid #29A329;
  border-radius: 8px;
  margin-bottom: 16px;
  background: #fff;
  padding: 0;
}

.faq-accordion summary {
  padding: 16px 20px;
  font-weight: bold;
  cursor: pointer;
  background-color: #1F75D6;
  color: #fff;
  border-radius: 8px;
  list-style: none;
}

.faq-accordion summary::-webkit-details-marker {
  display: none;
}

.faq-accordion summary::after {
  content: ' ▶';
  float: right;
  transition: transform 0.3s ease;
}

.faq-accordion details[open] summary::after {
  transform: rotate(90deg);
}

.faq-content {
  padding: 14px 20px 20px;
  color: #4C5562;
  line-height: 1.6;
}

.faq-content hr {
  border: none;
  height: 1px;
  background: #29A329;
  margin: 10px 0;
}

/* Responsive adjustments */
@media (max-width: 900px) {
  .work-strands {
    flex-direction: column;
    gap: 15px;
  }

  .ws-card {
    flex: 1 1 100%;
  }
}
</style>
