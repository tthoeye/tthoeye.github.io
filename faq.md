---
title: FAQ
layout: fullwidth
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
  margin: 8px 0 36px;
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
.oc2 .page-hero-sub {
  font-size: 16px;
  color: var(--grey);
  line-height: 1.7;
  max-width: 680px;
  margin: 0 auto;
}

/* ── BLOCK ── */
.oc2 .block { border-radius: 14px; padding: 40px; margin-bottom: 24px; }
.oc2 .block-grey { background: var(--grey-tint); border: 1.5px solid var(--grey-pale); }
.oc2 .block-blue { background: var(--blue-tint); border: 1.5px solid var(--blue-pale); }

/* ── WORK STRANDS GRID ── */
.oc2 .strands-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-bottom: 28px;
}
.oc2 .strand-intro {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-top: 4px solid var(--yellow);
  border-radius: 10px;
  padding: 28px 24px;
  transition: box-shadow 0.2s;
}
.oc2 .strand-intro:hover { box-shadow: 0 6px 20px rgba(31,117,214,0.10); }
.oc2 .strand-num { font-size: 36px; font-weight: 700; color: var(--blue-pale); line-height: 1; margin-bottom: 8px; }
.oc2 .strand-intro h3 { font-size: 15px !important; font-weight: 700; color: var(--ink); margin-bottom: 8px !important; }
.oc2 .strand-intro p  { font-size: 13.5px; color: var(--grey-mid); line-height: 1.7; }

/* ── RESOURCES ── */
.oc2 .resources-list {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.oc2 .resource-link {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 10px 14px;
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-radius: 8px;
  font-size: 13.5px;
  font-weight: 700;
  color: var(--blue) !important;
  transition: border-color 0.15s, background 0.15s;
}
.oc2 .resource-link:hover { border-color: var(--green); color: var(--green) !important; background: var(--green-tint); }

/* ── FAQ ACCORDION ── */
.oc2 .faq-list {
  display: flex;
  flex-direction: column;
  gap: 12px;
  margin-bottom: 8px;
}
.oc2 details {
  background: #fff;
  border: 1.5px solid var(--grey-pale);
  border-radius: 10px;
  overflow: hidden;
  transition: box-shadow 0.2s;
}
.oc2 details[open] {
  box-shadow: 0 4px 18px rgba(31,117,214,0.09);
  border-color: var(--blue-pale);
}
.oc2 summary {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 18px 24px;
  font-size: 15px;
  font-weight: 700;
  color: #fff;
  background: var(--blue);
  cursor: pointer;
  list-style: none;
  gap: 16px;
}
.oc2 summary::-webkit-details-marker { display: none; }
.oc2 summary::after {
  content: '▶';
  font-size: 11px;
  flex-shrink: 0;
  transition: transform 0.25s;
  opacity: 0.8;
}
.oc2 details[open] summary::after { transform: rotate(90deg); }

/* Alternate odd accordions green */
.oc2 .faq-list details:nth-child(even) summary { background: var(--green); }
.oc2 .faq-list details:nth-child(even)[open] { border-color: var(--green-pale); box-shadow: 0 4px 18px rgba(41,163,41,0.09); }
.oc2 .faq-list details:nth-child(even) .faq-a a { color: var(--green); }

/* Every third accordion yellow */
.oc2 .faq-list details:nth-child(3n) summary { background: var(--yellow); color: var(--ink); }
.oc2 .faq-list details:nth-child(3n)[open] { border-color: var(--yellow-pale); box-shadow: 0 4px 18px rgba(245,180,0,0.12); }
.oc2 .faq-list details:nth-child(3n) .faq-a a { color: #b07f00; }

/* ── FAQ CONTENT ── */
.oc2 .faq-body {
  padding: 0 24px 24px;
}
.oc2 .faq-item {
  padding: 20px 0;
  border-bottom: 1px solid var(--grey-pale);
}
.oc2 .faq-item:last-child { border-bottom: none; }
.oc2 .faq-q {
  font-size: 14px;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 8px;
}
.oc2 .faq-a {
  font-size: 13.5px;
  color: var(--grey-mid);
  line-height: 1.75;
}
.oc2 .faq-a p { margin-bottom: 10px; }
.oc2 .faq-a p:last-child { margin-bottom: 0; }
.oc2 .faq-a ul, .oc2 .faq-a ol {
  padding-left: 20px;
  margin: 8px 0 10px;
}
.oc2 .faq-a li { margin-bottom: 5px; }
.oc2 .faq-a a { color: var(--blue); font-weight: 600; }
.oc2 .faq-a a:hover { text-decoration: underline; }
.oc2 .faq-a strong { color: var(--ink); }

/* ── RESPONSIVE ── */
@media (max-width: 768px) {
  .oc2 { padding: 0 16px; }
  .oc2 .page-hero { padding: 28px 20px; }
  .oc2 .strands-grid { grid-template-columns: 1fr; }
  .oc2 .block { padding: 24px; }
  .oc2 summary { padding: 14px 18px; font-size: 14px; }
  .oc2 .faq-body { padding: 0 18px 20px; }
}
</style>

<div class="oc2" style="padding-top: 40px; padding-bottom: 56px;">

  <!-- HERO -->
  <div class="page-hero">
    <div class="sec-label" style="justify-content:center;">LDT4SSC</div>
    <h1>Helpdesk &amp; <span class="accent">FAQ</span></h1>
    <p class="page-hero-sub">Find answers to the most common questions about the LDT4SSC project, the Knowledge Hub, and how to get in touch with the team.</p>
  </div>

  <!-- ABOUT THE PROJECT -->
  <div class="sec-label">About the Project</div>
  <h2 class="sec-title">About the LDT4SSC Project</h2>
  <p class="sec-sub"><strong>Local Digital Twins for Smart and Sustainable Communities (LDT4SSC)</strong> is a European project supporting cities, regions and public authorities in the development, interconnection and enhancement of Local Digital Twins (LDTs). The project builds a federated, interoperable and reusable European ecosystem of LDTs, aligned with common standards, data spaces and the SIMPL framework. Funding and technical support are provided via Open Calls for Pilots.</p>

  <!-- WORK STRANDS -->
  <div class="strands-grid">
    <div class="strand-intro" style="border-top-color: var(--blue);">
      <div class="strand-num">WS1</div>
      <h3>Interconnecting Existing Local Digital Twins</h3>
      <p>Connects operational LDTs for cross-border data exchange, shared services and interoperability.</p>
    </div>
    <div class="strand-intro" style="border-top-color: var(--green);">
      <div class="strand-num">WS2</div>
      <h3>Creating New Local Digital Twins Based on Common Needs</h3>
      <p>Co-design and deploy new LDTs addressing shared urban challenges.</p>
    </div>
    <div class="strand-intro" style="border-top-color: var(--yellow);">
      <div class="strand-num">WS3</div>
      <h3>Adding Advanced AI-Based Capabilities to LDTs</h3>
      <p>Develops advanced AI-driven predictive and immersive services on LDTs.</p>
    </div>
  </div>

  <!-- RESOURCES -->
  <div class="block" style="background: var(--green-tint); border: 1.5px solid var(--green-pale); margin-bottom:36px;">
    <div class="sec-label" style="color: var(--green); margin-bottom:12px;">
      <span style="background: var(--green);"></span>Useful Documents &amp; Links</div>
    <div class="resources-list">
      <a href="https://ldt4ssc.eu/opencalls/" class="resource-link">🔗 LDT4SSC Open Calls pages</a>
      <a href="https://ldt4ssc.eu/call-two/" class="resource-link">📄 Call for Pilots Manual</a>
      <a href="https://ldt4ssc.eu/call-two/" class="resource-link">📝 Application forms and templates per Work Strand</a>
      <a href="https://www.b2match.com/e/local-digital-twins-smart-communities" class="resource-link">🤝 Matchmaking Platform</a>
      <a href="https://ldt4ssc.eu/news/" class="resource-link">📰 News &amp; Events page</a>
    </div>
    <p style="margin-top:16px; font-size:13.5px; color:var(--grey-mid);">All documents and links are available on the official <a href="https://ldt4ssc.eu/" style="color:var(--blue); font-weight:600;">LDT4SSC website</a>.</p>
  </div>

  <div class="sec-divider"></div>

  <!-- FAQ -->
  <div class="sec-label">FAQ</div>
  <h2 class="sec-title">Frequently Asked Questions</h2>
  <p class="sec-sub" style="margin-bottom:28px;">Browse by topic to find answers to common questions about the open calls, eligibility, funding and more.</p>

  <div class="faq-list">

    <!-- 1 -->
    <details>
      <summary>Calls, Timelines &amp; Information Availability</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: Where can I find official information on call timelines, requirements and eligibility?</div>
          <div class="faq-a"><p>All official and up-to-date information is provided in the Call for Pilots Manual, available on the LDT4SSC website. This document outlines eligibility criteria, consortium requirements, scope and evaluation procedures.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: When will more details on upcoming calls be published?</div>
          <div class="faq-a">
            <p>Further details on upcoming calls, particularly for Work Strands 2 and 3, will be published closer to their launch dates, as indicated in the Call for Pilots Manual. Both WS2 and WS3 will feature two Open Call windows each, offering multiple opportunities to apply.</p>
            <p>Applicants are encouraged to:</p>
            <ul>
              <li>Regularly check the LDT4SSC website</li>
              <li>Follow project communication channels</li>
              <li>Consult the News and Events section for updates and information sessions</li>
            </ul>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: Can information about submitted or selected applications be shared?</div>
          <div class="faq-a"><p>No. Information about submitted applications or evaluation outcomes cannot be disclosed before the formal evaluation process is completed.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q4: How many Open Calls are planned in LDT4SSC?</div>
          <div class="faq-a"><p>There are five Open Calls planned within the LDT4SSC project. An overview is available on the official LDT4SSC website.</p></div>
        </div>
      </div>
    </details>

    <!-- 2 -->
    <details>
      <summary>Local Digital Twins: Concepts, Tools and Standards</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: What is a Local Digital Twin?</div>
          <div class="faq-a"><p>A Local (or Urban) Digital Twin is a digital representation of physical assets, systems or processes within a defined local context (e.g. city, district, building, port or airport). It uses historical, near real-time or real-time data to enable visualisation, analysis, simulation and decision-making. For additional information please refer to the <a href="https://knowledgehub.ldt4ssc.eu/resources_content/tech_resources/#what-is-a-local-digital-twin" target="_blank">Knowledge Hub</a>.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: What tools are available to support Digital Twin development?</div>
          <div class="faq-a"><p>Available tools include the EU Local Digital Twin Toolbox, the SIMPL middleware, and a range of open-source components referenced in the Call documentation and collected in the Resources for Pilots section on the project's <a href="https://knowledgehub.ldt4ssc.eu/resources_content/tech_resources/#what-is-a-local-digital-twin" target="_blank">Knowledge Hub</a>.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: How can existing Local Digital Twins (LDTs) be further developed? (WS1 &amp; WS3)</div>
          <div class="faq-a"><p>Pilots are expected to expand existing LDTs by interconnecting to other LDTs, developing and further improving open-source components, proposing new services that improve decision-making, resilience and sustainability.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q4: How is interoperability between cities ensured?</div>
          <div class="faq-a">
            <p>Pilots must adopt open specifications and standards (e.g. DCAT, ODRL) and use the SIMPL framework to ensure interoperable and cost-effective architectures across cities.</p>
            <p><a href="https://mims.oascities.org/" target="_blank">Minimal Interoperability Mechanisms Plus (MIMs)</a> provides a common set of standard specifications that enable a minimal but sufficient level of interoperability for data, systems, and services specifically across cities and communities in Europe.</p>
            <p>Cities can also rely on the <a href="https://interoperable-europe.ec.europa.eu/collection/iopeu-monitoring/european-interoperability-framework" target="_blank">European Interoperability Framework (EIF)</a>, which gives specific guidance on how to set up interoperable digital public services.</p>
            <p>Building on the EIF and MIMs Plus, the <a href="https://digital-strategy.ec.europa.eu/en/news/proposal-european-interoperability-framework-smart-cities-and-communities-eif4scc" target="_blank">Proposal for a European Interoperability Framework for Smart Cities and Communities (EIF4SCC)</a> offers definitions, principles, recommendations, and practical use cases to guide cities in delivering cross-border, cross-domain services to the public.</p>
            <p>The LDT4SSC project will provide materials and specific training to awarded pilots, guiding them in implementing these frameworks and mechanisms.</p>
          </div>
        </div>
      </div>
    </details>

    <!-- 3 -->
    <details>
      <summary>Eligibility Rules for Applying to the Open Calls</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: Is participation in one Work Strand mandatory to apply for another?</div>
          <div class="faq-a"><p>No. Applicants may choose to apply to one or more Work Strands, depending on their objectives and capacity. Participation in a specific Work Strand is not a prerequisite for applying to another.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: Is membership in the LDT CitiVERSE EDIC required to apply?</div>
          <div class="faq-a"><p>No. Participation in the LDT4SSC Calls for Pilots is not linked to membership in the LDT CitiVERSE EDIC. Being a member does not provide any advantage, nor is it required for eligibility.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: Am I eligible if my organisation is based outside the Digital Europe Programme (DEP)?</div>
          <div class="faq-a"><p>No. Only organisations based in eligible DEP countries can receive funding and participate in pilot consortia. Organisations based in non-DEP countries are not eligible.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q4: Can an agency working for a city (e.g. mobility agency, waste management agency) participate in these calls?</div>
          <div class="faq-a"><p>Yes, any partner regardless of the legal status can participate in a consortium, as long as the requirement of having two LRAs represented in the consortium is met. If your agency is considered a public sector agency owned by the municipality, and you are officially representing the city government, there is no issue for you to be considered one of the needed public sector partners in a consortium.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q5: Can a city with an existing LDT participate in WS2?</div>
          <div class="faq-a"><p>If you already have an LDT in place, it can serve as a basis to develop new cases in the LDT, by complying with the technical and non-technical requirements of the call and in collaboration with at least one other city or community.</p></div>
        </div>
      </div>
    </details>

    <!-- 4 -->
    <details>
      <summary>Timeframes &amp; Maturity</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: What is the expected duration of pilot projects?</div>
          <div class="faq-a"><p>Pilots are expected to last between 12 and 18 months.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: How can municipalities assess their readiness to apply?</div>
          <div class="faq-a"><p>Municipalities can use the LORDIMAS framework to assess their digital maturity and readiness for participating in different Work Strands. Completing this assessment is recommended for applying but not mandatory. Applicants can find recommendations on the level of maturity to have upon application and to be achieved by the end of the piloting at the LORDIMAS assessment in the CfP Manual.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: What if the timeline of a call does not fit our readiness?</div>
          <div class="faq-a"><p>No deadline extensions are provided. However, the LDT4SSC project includes five Open Calls, offering multiple opportunities to apply over time.</p></div>
        </div>
      </div>
    </details>

    <!-- 5 -->
    <details>
      <summary>Funding &amp; Budget</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: What if the funding model is not suitable for our organisation?</div>
          <div class="faq-a"><p>If an organisation cannot meet the 50% co-funding requirement, it is not eligible to participate under the LDT4SSC Calls for Pilots.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: How should the 50% co-funding requirement be allocated within the consortium?</div>
          <div class="faq-a"><p>The consortium must demonstrate that it collectively meets the 50% co-funding requirement. How individual partners contribute to this total is not a determining factor, as long as the consortium as a whole complies.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: How much funding can a consortium receive?</div>
          <div class="faq-a"><p>Each consortium may receive up to €1,000,000, with a maximum of €500,000 per third party, subject to the specific conditions of each Work Strand.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q4: Can pilots demonstrate financial eligibility through in-kind contributions as well as monetary support?</div>
          <div class="faq-a"><p>No, financial eligibility can only be demonstrated through monetary support only.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q5: How many projects will be funded in each Work Strand?</div>
          <div class="faq-a"><p>LDT4SSC will fund as many projects as there is budget to do so.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q6: Can a city / public entity partially cover the eligible costs with ERDF (European Regional Development Fund)?</div>
          <div class="faq-a"><p>Synergy grants might be used as co-funding, but in case you plan to do so, please let us know as soon as possible because this will need to be checked with the European Commission's internal financial services.</p></div>
        </div>
      </div>
    </details>

    <!-- 6 -->
    <details>
      <summary>Consortium Building</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: How can organisations find partners or join a consortium?</div>
          <div class="faq-a">
            <p>The recommended way to connect with potential partners is through the LDT4SSC Matchmaking Platform, which is specifically designed to support consortium building for the Open Calls. Through the platform, organisations can:</p>
            <ul>
              <li>Create a profile describing their expertise, interests and role</li>
              <li>Publish a project idea or consortium proposal</li>
              <li>Search for and contact cities, SMEs, research organisations and other stakeholders</li>
              <li>Initiate meetings and consortium discussions directly with potential partners</li>
            </ul>
            <p>The Matchmaking Platform is <a href="https://www.b2match.com/e/local-digital-digital-twins-smart-communities" target="_blank">available here</a>.</p>
            <p>A short tutorial on how to use the platform is also <a href="https://youtu.be/T1SeHtgg5ew?si=jdSJ6Boz8ibA9Cl5" target="_blank">available on YouTube</a>.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: Can a consortium be formed after submitting an application?</div>
          <div class="faq-a"><p>No. Applications must be submitted by a fully formed consortium. Consortia are expected to implement their pilots independently and cannot merge or partner with other consortia after submission.</p></div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: Can third parties apply as leads to the consortium?</div>
          <div class="faq-a"><p>While there is a preference for a public authority to act as lead, third parties can also do so.</p></div>
        </div>
      </div>
    </details>

    <!-- 7 -->
    <details>
      <summary>Pilots &amp; Evaluation</summary>
      <div class="faq-body">
        <div class="faq-item">
          <div class="faq-q">Q1: How will pilot proposals be evaluated?</div>
          <div class="faq-a">
            <p>Applications undergo evaluation as follows:</p>
            <ul>
              <li>A pre-screening (eligibility check) — pass/fail assessment</li>
              <li>Full evaluation by the Evaluation Committee and Ethical Board</li>
              <li>Validation by the Steering Committee</li>
            </ul>
            <p>Only proposals that pass the eligibility check proceed to the full evaluation.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q2: What is checked during the eligibility screening?</div>
          <div class="faq-a">
            <p>The eligibility check verifies that:</p>
            <ul>
              <li>All required documents were submitted on time and in the correct format (pdf &amp; excel)</li>
              <li>The proposal does not deviate from the official template and comply with the page limits</li>
              <li>All required questions are completed</li>
              <li>The consortium composition meets the eligibility rules</li>
              <li>The 50% co-funding requirement is met</li>
              <li>The funding limits are respected</li>
              <li>The minimum technical and non-technical requirements are respected</li>
            </ul>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q3: What criteria are used to evaluate proposals?</div>
          <div class="faq-a">
            <p>Proposals are evaluated based on excellence, impact, and quality &amp; efficiency of implementation:</p>
            <ul>
              <li><strong>Excellence:</strong> clarity of objectives, alignment with EU priorities, quality of use cases, technical and functional architecture, robust data governance and ethics approach, sound methodology</li>
              <li><strong>Impact:</strong> measurable socio-economic and environmental benefits, replicability across EU communities, contribution to the EU LDT ecosystem, stakeholder engagement, sustainability and scaling strategy</li>
              <li><strong>Quality &amp; Efficiency of implementation:</strong> consortium expertise, work plan realism, resource allocation, risk management, technical maturity</li>
            </ul>
            <p>Each criterion has a minimum score of 6 and a maximum of 10. Proposals must reach the minimum threshold in each category. More information can be found in the CfP Manual.</p>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q4: What are the use-case eligibility criteria for each Work Strand?</div>
          <div class="faq-a">
            <ul>
              <li><strong>Work Strand 1:</strong> at least two cross-sectoral use cases; each must feature one shared service integrating datasets from at least two different sectors</li>
              <li><strong>Work Strand 2:</strong> at least one cross-sectoral, innovative and citizen-focused use case; each must feature two services addressing a shared local challenge and common need</li>
              <li><strong>Work Strand 3:</strong> at least one cross-sectoral, innovative and citizen-focused use case; each must feature two services addressing a shared local challenge</li>
            </ul>
          </div>
        </div>
        <div class="faq-item">
          <div class="faq-q">Q5: What are the technical eligibility criteria?</div>
          <div class="faq-a">
            <ul>
              <li><strong>Work Strand 1:</strong> interconnection of two digitally mature existing LDTs with at least descriptive-level capabilities and dynamic data integration</li>
              <li><strong>Work Strands 2 &amp; 3:</strong> development of a new common LDT with at least two instances (one per public authority) and advanced simulation capability (predictive, prospective or prescriptive). WS2 focuses on new LDT capacities based on shared needs; WS3 concerns advanced or AI-enabled services building on LDT frameworks.</li>
            </ul>
            <p>Please refer to the applicable <a href="https://ldt4ssc.eu/documents/cpmws1.pdf" target="_blank">WS1</a>, <a href="https://ldt4ssc.eu/documents/cpmws2.pdf" target="_blank">WS2</a> and <a href="https://ldt4ssc.eu/documents/cpmws3.pdf" target="_blank">WS3</a> Call for Pilots Manuals for further information.</p>
          </div>
        </div>
      </div>
    </details>

  </div>

</div>
