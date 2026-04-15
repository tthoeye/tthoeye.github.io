---
title: FAQ
layout: faq
bodyClass: "page-faq"
description: Frequently Asked Questions
permalink: /faq/
intro_image_absolute: false
intro_image_hide_on_mobile: true
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
.oc2 .btn-outline { background: #fff; border: 2px solid var(--blue); color: var(--blue) !important; }
.oc2 .btn-outline:hover { background: var(--blue-tint); filter: none; }

/* Hero */
.oc2 .hero {
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-radius: 14px;
  padding: 48px;
  margin-bottom: 40px;
}
.oc2 .hero h1 { font-family: Arial, Helvetica, sans-serif !important; font-size: clamp(26px, 3vw, 44px) !important; font-weight: 700 !important; color: var(--ink) !important; line-height: 1.1 !important; margin-bottom: 16px !important; border: none !important; padding: 0 !important; }
.oc2 .hero h1 .accent { color: var(--blue); }
.oc2 .hero-sub { font-size: 15px; color: var(--grey); line-height: 1.7; }

/* Work strands */
.oc2 .ws-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 18px; margin-bottom: 36px; }
.oc2 .ws-card { background: #fff; border: 1.5px solid var(--grey-pale); border-top: 4px solid var(--yellow); border-radius: 10px; padding: 24px; transition: box-shadow 0.2s; }
.oc2 .ws-card:hover { box-shadow: 0 6px 20px rgba(31,117,214,0.10); }
.oc2 .ws-card h4 { font-size: 14px !important; font-weight: 700; color: var(--blue); margin-bottom: 8px !important; line-height: 1.3; }
.oc2 .ws-card p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

/* Resources */
.oc2 .resources-list { display: flex; flex-direction: column; gap: 8px; }
.oc2 .res-link { display: flex; align-items: center; gap: 10px; padding: 10px 14px; background: #fff; border: 1.5px solid var(--grey-pale); border-radius: 8px; font-size: 13.5px; font-weight: 700; color: var(--blue) !important; transition: border-color 0.15s, background 0.15s; }
.oc2 .res-link:hover { border-color: var(--blue); background: var(--blue-tint); }

/* Block */
.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); }
.oc2 .two-col-block { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: start; }

/* FAQ Accordion */
.oc2 .faq-item { background: #fff; border: 1.5px solid var(--grey-pale); border-left: 4px solid var(--green); border-radius: 10px; margin-bottom: 10px; overflow: hidden; transition: border-color 0.2s, box-shadow 0.2s; }
.oc2 .faq-item:hover { border-color: var(--green); box-shadow: 0 4px 16px rgba(41,163,41,0.08); }
.oc2 .faq-item[open] { border-color: var(--green); box-shadow: 0 4px 16px rgba(41,163,41,0.10); }
.oc2 .faq-summary {
  padding: 18px 22px;
  font-weight: 700;
  font-size: 15px;
  color: var(--ink);
  cursor: pointer;
  background: var(--green-tint);
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  list-style: none;
  user-select: none;
}
.oc2 .faq-summary::-webkit-details-marker { display: none; }
.oc2 .faq-summary::after {
  content: '';
  width: 20px; height: 20px;
  border-radius: 50%;
  background: var(--green-pale);
  border: 1.5px solid var(--green);
  flex-shrink: 0;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 20 20'%3E%3Cpath d='M5 8l5 5 5-5' stroke='%2329A329' stroke-width='2' fill='none' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 14px;
  transition: transform 0.2s;
}
.oc2 .faq-item[open] .faq-summary::after { transform: rotate(180deg); }
.oc2 .faq-item[open] .faq-summary { border-bottom: 1.5px solid var(--green-pale); }
.oc2 .faq-body { padding: 0; }

.oc2 .faq-q { padding: 20px 22px 4px; }
.oc2 .faq-q-label { font-size: 11px; font-weight: 700; letter-spacing: 0.10em; text-transform: uppercase; color: var(--green); margin-bottom: 4px; }
.oc2 .faq-q-text { font-size: 14px; font-weight: 700; color: var(--ink); line-height: 1.4; }
.oc2 .faq-a { padding: 6px 22px 20px; }
.oc2 .faq-a-text { font-size: 13.5px; color: var(--grey-mid); line-height: 1.75; }
.oc2 .faq-a-text a { color: var(--blue); font-weight: 600; }
.oc2 .faq-a-text a:hover { text-decoration: underline; }
.oc2 .faq-a-text ul, .oc2 .faq-a-text ol { padding-left: 20px; margin-top: 8px; }
.oc2 .faq-a-text li { margin-bottom: 5px; }
.oc2 .faq-sep { height: 1px; background: var(--green-pale); margin: 0 22px; }

@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .hero { padding: 28px; }
  .oc2 .ws-grid { grid-template-columns: 1fr; }
  .oc2 .two-col-block { grid-template-columns: 1fr; gap: 24px; }
  .oc2 .block { padding: 24px; }
}
</style>

<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <!-- Hero -->
  <div class="hero">
    <div class="sec-label">Help &amp; Support</div>
    <h1>Frequently Asked <span class="accent">Questions</span></h1>
    <p class="hero-sub">Find answers to the most common questions about the LDT4SSC project, the Open Calls, eligibility, funding and how to get in touch with the team.</p>
  </div>

  <!-- About section -->
  <div class="sec-label">About the Project</div>
  <h2 class="sec-title">About the LDT4SSC Project</h2>
  <p class="sec-sub"><strong>Local Digital Twins for Smart and Sustainable Communities (LDT4SSC)</strong> is a European project supporting cities, regions and public authorities in the development, interconnection and enhancement of Local Digital Twins (LDTs). The project builds a federated, interoperable and reusable European ecosystem of LDTs, aligned with common standards, data spaces and the SIMPL framework. Funding and technical support are provided via Open Calls for Pilots.</p>

  <div class="ws-grid">
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

  <div class="sec-divider"></div>

  <!-- Resources -->
  <div class="block block-grey" style="margin-bottom: 36px;">
    <div class="two-col-block">
      <div>
        <div class="sec-label" style="margin-bottom: 8px;">Useful Documents &amp; Links</div>
        <h2 class="sec-title" style="font-size: clamp(18px, 2vw, 24px); margin-bottom: 16px;">Key Resources</h2>
        <p style="font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 20px;">All documents and links are available on the official <a href="https://ldt4ssc.eu/" style="color: var(--blue); font-weight: 600;">LDT4SSC website</a>.</p>
        <div class="resources-list">
          <a href="https://ldt4ssc.eu/opencalls/" class="res-link">→ LDT4SSC Open Calls pages</a>
          <a href="https://ldt4ssc.eu/call-two/" class="res-link">→ Call for Pilots Manual</a>
          <a href="https://ldt4ssc.eu/call-two/" class="res-link">→ Application forms and templates per Work Strand</a>
          <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="res-link">→ Matchmaking Platform</a>
          <a href="https://ldt4ssc.eu/news/" class="res-link">→ News &amp; Events page</a>
        </div>
      </div>
      <div>
        <div class="sec-label" style="margin-bottom: 8px;">Get Involved</div>
        <h2 class="sec-title" style="font-size: clamp(18px, 2vw, 24px); margin-bottom: 16px;">Connect &amp; Stay Updated</h2>
        <p style="font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; margin-bottom: 20px;">Looking to connect with partners, ask a question or stay up to date with the latest news?</p>
        <div style="display: flex; flex-direction: column; gap: 10px;">
          <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="btn btn-blue" style="justify-content: center;">Find partners via Matchmaking Platform</a>
          <a href="https://shorturl.at/pzMGK" class="btn btn-outline" style="justify-content: center;">Subscribe to the newsletter</a>
        </div>
      </div>
    </div>
  </div>

  <div class="sec-divider"></div>

  <!-- FAQ -->
  <div class="sec-label">FAQ</div>
  <h2 class="sec-title">Common Questions</h2>
  <p class="sec-sub">Browse the sections below to find answers. Click any topic to expand it.</p>

  <!-- 1 -->
  <details class="faq-item">
    <summary class="faq-summary">Calls, Timelines &amp; Information Availability</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">Where can I find official information on call timelines, requirements and eligibility?</div></div>
      <div class="faq-a"><div class="faq-a-text">All official and up-to-date information is provided in the Call for Pilots Manual, available on the LDT4SSC website. This document outlines eligibility criteria, consortium requirements, scope and evaluation procedures.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">When will more details on upcoming calls be published?</div></div>
      <div class="faq-a"><div class="faq-a-text">Further details on upcoming calls, particularly for Work Strands 2 and 3, will be published closer to their launch dates, as indicated in the Call for Pilots Manual. Both WS2 and WS3 will feature two Open Call windows each, offering multiple opportunities to apply.<ul><li>Regularly check the LDT4SSC website</li><li>Follow project communication channels</li><li>Consult the News and Events section for updates and information sessions</li></ul></div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">Can information about submitted or selected applications be shared?</div></div>
      <div class="faq-a"><div class="faq-a-text">No. Information about submitted applications or evaluation outcomes cannot be disclosed before the formal evaluation process is completed.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q4</div><div class="faq-q-text">How many Open Calls are planned in LDT4SSC?</div></div>
      <div class="faq-a"><div class="faq-a-text">There are five Open Calls planned within the LDT4SSC project. An overview is available on the official LDT4SSC website.</div></div>
    </div>
  </details>

  <!-- 2 -->
  <details class="faq-item">
    <summary class="faq-summary">Local Digital Twins: Concepts, Tools and Standards</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">What is a Local Digital Twin?</div></div>
      <div class="faq-a"><div class="faq-a-text">A Local (or Urban) Digital Twin is a digital representation of physical assets, systems or processes within a defined local context (e.g. city, district, building, port or airport). It uses historical, near real-time or real-time data to enable visualisation, analysis, simulation and decision-making. For additional information please refer to the <a href="https://knowledgehub.ldt4ssc.eu/resources_content/tech_resources/#what-is-a-local-digital-twin" target="_blank">Knowledge Hub</a>.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">What tools are available to support Digital Twin development?</div></div>
      <div class="faq-a"><div class="faq-a-text">Available tools include the EU Local Digital Twin Toolbox, the SIMPL middleware, and a range of open-source components referenced in the Call documentation and collected in the Resources for Pilots section on the project's <a href="https://knowledgehub.ldt4ssc.eu/resources_content/tech_resources/#what-is-a-local-digital-twin" target="_blank">Knowledge Hub</a>.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">How can existing Local Digital Twins (LDTs) be further developed? (WS1 &amp; WS3)</div></div>
      <div class="faq-a"><div class="faq-a-text">Pilots are expected to expand existing LDTs by interconnecting to other LDTs, developing and further improving open-source components, and proposing new services that improve decision-making, resilience and sustainability.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q4</div><div class="faq-q-text">How is interoperability between cities ensured?</div></div>
      <div class="faq-a"><div class="faq-a-text">Pilots must adopt open specifications and standards (e.g. DCAT, ODRL) and use the SIMPL framework to ensure interoperable and cost-effective architectures across cities.<br><br><a href="https://mims.oascities.org/" target="_blank">Minimal Interoperability Mechanisms Plus (MIMs)</a> provides a common set of standard specifications enabling a minimal but sufficient level of interoperability for data, systems, and services across cities and communities in Europe.<br><br>Cities can also rely on the <a href="https://interoperable-europe.ec.europa.eu/collection/iopeu-monitoring/european-interoperability-framework" target="_blank">European Interoperability Framework (EIF)</a>, which gives specific guidance on how to set up interoperable digital public services across four layers: Legal, Organisational, Semantic, and Technical.<br><br>Building on the EIF and MIMs Plus, the <a href="https://digital-strategy.ec.europa.eu/en/news/proposal-european-interoperability-framework-smart-cities-and-communities-eif4scc" target="_blank">European Interoperability Framework for Smart Cities and Communities (EIF4SCC)</a> offers definitions, principles, recommendations, and practical use cases to guide cities in delivering cross-border, cross-domain services.<br><br>The LDT4SSC project will provide materials and specific training to awarded pilots, guiding them in implementing these frameworks and mechanisms.</div></div>
    </div>
  </details>

  <!-- 3 -->
  <details class="faq-item">
    <summary class="faq-summary">Eligibility Rules for Applying to the Open Calls</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">Is participation in one Work Strand mandatory to apply for another?</div></div>
      <div class="faq-a"><div class="faq-a-text">No. Applicants may choose to apply to one or more Work Strands, depending on their objectives and capacity. Participation in a specific Work Strand is not a prerequisite for applying to another.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">Is membership in the LDT CitiVERSE EDIC required to apply?</div></div>
      <div class="faq-a"><div class="faq-a-text">No. Participation in the LDT4SSC Calls for Pilots is not linked to membership in the LDT CitiVERSE EDIC. Being a member does not provide any advantage, nor is it required for eligibility.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">Am I eligible if my organisation is based outside the Digital Europe Programme (DEP)?</div></div>
      <div class="faq-a"><div class="faq-a-text">No. Only organisations based in eligible DEP countries can receive funding and participate in pilot consortia. Organisations based in non-DEP countries are not eligible.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q4</div><div class="faq-q-text">Can an agency working for a city (e.g. mobility agency, waste management agency) participate in these calls?</div></div>
      <div class="faq-a"><div class="faq-a-text">Yes, any partner regardless of legal status can participate in a consortium, as long as the requirement of having two LRAs represented in the consortium is met. If your agency is considered a public sector agency owned by the municipality and you officially represent the city government, there is no issue for you to be considered one of the needed public sector partners in a consortium.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q5</div><div class="faq-q-text">Can a city with an existing LDT participate in WS2?</div></div>
      <div class="faq-a"><div class="faq-a-text">If you already have an LDT in place, it can serve as a basis to develop new cases in the LDT, by complying with the technical and non-technical requirements of the call and in collaboration with at least one other city or community.</div></div>
    </div>
  </details>

  <!-- 4 -->
  <details class="faq-item">
    <summary class="faq-summary">Timeframes &amp; Maturity</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">What is the expected duration of pilot projects?</div></div>
      <div class="faq-a"><div class="faq-a-text">Pilots are expected to last between 12 and 18 months.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">How can municipalities assess their readiness to apply?</div></div>
      <div class="faq-a"><div class="faq-a-text">Municipalities can use the LORDIMAS framework to assess their digital maturity and readiness for participating in different Work Strands. Completing this assessment is recommended for applying but not mandatory. Applicants can find recommendations on the level of maturity to have upon application and to be achieved by the end of the piloting at the LORDIMAS assessment in the CfP Manual.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">What if the timeline of a call does not fit our readiness?</div></div>
      <div class="faq-a"><div class="faq-a-text">No deadline extensions are provided. However, the LDT4SSC project includes five Open Calls, offering multiple opportunities to apply over time.</div></div>
    </div>
  </details>

  <!-- 5 -->
  <details class="faq-item">
    <summary class="faq-summary">Funding &amp; Budget</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">What if the funding model is not suitable for our organisation?</div></div>
      <div class="faq-a"><div class="faq-a-text">If an organisation cannot meet the 50% co-funding requirement, it is not eligible to participate under the LDT4SSC Calls for Pilots.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">How should the 50% co-funding requirement be allocated within the consortium?</div></div>
      <div class="faq-a"><div class="faq-a-text">The consortium must demonstrate that it collectively meets the 50% co-funding requirement. How individual partners contribute to this total is not a determining factor, as long as the consortium as a whole complies.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">How much funding can a consortium receive?</div></div>
      <div class="faq-a"><div class="faq-a-text">Each consortium may receive up to €1,000,000, with a maximum of €500,000 per third party, subject to the specific conditions of each Work Strand.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q4</div><div class="faq-q-text">Can pilots demonstrate financial eligibility through in-kind contributions as well as monetary support?</div></div>
      <div class="faq-a"><div class="faq-a-text">No. Financial eligibility can only be demonstrated through monetary support.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q5</div><div class="faq-q-text">How many projects will be funded in each Work Strand?</div></div>
      <div class="faq-a"><div class="faq-a-text">LDT4SSC will fund as many projects as there is budget to do so.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q6</div><div class="faq-q-text">Can a city / public entity partially cover the eligible costs with ERDF (European Regional Development Fund)?</div></div>
      <div class="faq-a"><div class="faq-a-text">Synergy grants might be used as co-funding, but if you plan to do so, please let us know as soon as possible as this will need to be checked with the European Commission's internal financial services.</div></div>
    </div>
  </details>

  <!-- 6 -->
  <details class="faq-item">
    <summary class="faq-summary">Consortium Building</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">How can organisations find partners or join a consortium?</div></div>
      <div class="faq-a"><div class="faq-a-text">The recommended way to connect with potential partners is through the LDT4SSC Matchmaking Platform, which is specifically designed to support consortium building for the Open Calls. Through the platform, organisations can:<ul><li>Create a profile describing their expertise, interests and role</li><li>Publish a project idea or consortium proposal</li><li>Search for and contact cities, SMEs, research organisations and other stakeholders</li><li>Initiate meetings and consortium discussions directly with potential partners</li></ul><br>The Matchmaking Platform is <a href="https://www.b2match.com/e/local-digital-digital-twins-smart-communities" target="_blank">available here</a>. A short tutorial on how to use the platform is also <a href="https://youtu.be/T1SeHtgg5ew?si=jdSJ6Boz8ibA9Cl5" target="_blank">available on YouTube</a>.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">Can a consortium be formed after submitting an application?</div></div>
      <div class="faq-a"><div class="faq-a-text">No. Applications must be submitted by a fully formed consortium. Consortia are expected to implement their pilots independently and cannot merge or partner with other consortia after submission.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">Can third parties apply as leads to the consortium?</div></div>
      <div class="faq-a"><div class="faq-a-text">While there is a preference for a public authority to act as lead, third parties can also do so.</div></div>
    </div>
  </details>

  <!-- 7 -->
  <details class="faq-item" style="margin-bottom: 0;">
    <summary class="faq-summary">Pilots &amp; Evaluation</summary>
    <div class="faq-body">
      <div class="faq-q"><div class="faq-q-label">Q1</div><div class="faq-q-text">How will pilot proposals be evaluated?</div></div>
      <div class="faq-a"><div class="faq-a-text">Applications undergo evaluation as follows:<ul><li>A pre-screening (eligibility check) — pass/fail assessment</li><li>Full evaluation by the Evaluation Committee and Ethical Board</li><li>Validation by the Steering Committee</li></ul>Only proposals that pass the eligibility check proceed to the full evaluation.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q2</div><div class="faq-q-text">What is checked during the eligibility screening?</div></div>
      <div class="faq-a"><div class="faq-a-text">The eligibility check verifies that:<ul><li>All required documents were submitted on time and in the correct format (pdf &amp; excel)</li><li>The proposal does not deviate from the official template and complies with the page limits</li><li>All required questions are completed</li><li>The consortium composition meets the eligibility rules</li><li>The 50% co-funding requirement is met</li><li>The funding limits are respected</li><li>The minimum technical and non-technical requirements are respected</li></ul></div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q3</div><div class="faq-q-text">What criteria are used to evaluate proposals?</div></div>
      <div class="faq-a"><div class="faq-a-text">Proposals are evaluated based on three criteria:<ul><li><strong style="color: var(--ink);">Excellence:</strong> Clarity of objectives, alignment with EU priorities, quality of use cases, technical and functional architecture, robust data governance and ethics approach, and sound methodology.</li><li><strong style="color: var(--ink);">Impact:</strong> Measurable socio-economic and environmental benefits, replicability across EU communities, contribution to the EU LDT ecosystem, stakeholder engagement, and sustainability and scaling strategy.</li><li><strong style="color: var(--ink);">Quality &amp; Efficiency of Implementation:</strong> Consortium expertise, work plan realism, resource allocation, risk management, and technical maturity.</li></ul>Each criterion has a minimum score of 6 and a maximum of 10. Proposals must reach the minimum threshold in each category. More information can be found in the CfP Manual.</div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q4</div><div class="faq-q-text">What are the use-case eligibility criteria for each Work Strand?</div></div>
      <div class="faq-a"><div class="faq-a-text"><ul><li><strong style="color: var(--ink);">Work Strand 1:</strong> At least two cross-sectoral use cases. Each use case must feature one shared service integrating datasets from at least two different sectors.</li><li><strong style="color: var(--ink);">Work Strand 2:</strong> At least one cross-sectoral, innovative and citizen-focused use case. Each use case must feature two services and address a shared local challenge and common need.</li><li><strong style="color: var(--ink);">Work Strand 3:</strong> At least one cross-sectoral, innovative and citizen-focused use case. Each use case must feature two services and address a shared local challenge.</li></ul></div></div>
      <div class="faq-sep"></div>
      <div class="faq-q"><div class="faq-q-label">Q5</div><div class="faq-q-text">What are the technical eligibility criteria?</div></div>
      <div class="faq-a"><div class="faq-a-text"><ul><li><strong style="color: var(--ink);">Work Strand 1:</strong> The interconnection of two digitally mature existing LDTs — meaning an existing LDT with at least descriptive-level capabilities and dynamic data integration.</li><li><strong style="color: var(--ink);">Work Strands 2 &amp; 3:</strong> The development of a new common LDT with at least two instances (one per public authority) and advanced simulation capability (predictive, prospective or prescriptive). WS2 focuses on developing new LDT capacities based on shared needs; WS3 concerns advanced or AI-enabled services building on LDT frameworks.</li></ul>Please refer to the applicable <a href="https://ldt4ssc.eu/documents/cpmws1.pdf" target="_blank">WS1</a>, <a href="https://ldt4ssc.eu/documents/cpmws2.pdf" target="_blank">WS2</a> and <a href="https://ldt4ssc.eu/documents/cpmws3.pdf" target="_blank">WS3</a> Call for Pilots Manuals for further information.</div></div>
    </div>
  </details>

</div>
