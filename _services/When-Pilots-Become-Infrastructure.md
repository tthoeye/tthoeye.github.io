---
title: "When Pilots Become Infrastructure: What Standards Deliver for European Local Digital Twins"
date: 2026-10-07
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
  margin-bottom: 8px;
}
.nw .nw-subtitle {
  font-size: clamp(16px, 2vw, 20px);
  font-weight: 600;
  color: var(--grey-mid);
  line-height: 1.3;
  margin-bottom: 18px;
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
.nw .nw-meta-pill.author {
  background: var(--green-tint);
  border-color: var(--green-pale);
  color: var(--green);
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

.nw .nw-source {
  font-size: 13.5px;
  color: var(--grey-mid);
  font-style: italic;
  margin-bottom: 14px;
}

.nw .nw-body h2 {
  font-size: 21px;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.25;
  margin: 36px 0 14px;
  padding-left: 14px;
  border-left: 4px solid var(--blue);
}
.nw .nw-body p {
  font-size: 15px;
  line-height: 1.8;
  margin-bottom: 16px;
}

.nw .nw-figure {
  margin: 28px 0 8px;
}
.nw .nw-figure img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 10px;
  border: 1.5px solid var(--grey-pale);
}
.nw .nw-figure figcaption {
  font-size: 12px;
  color: var(--grey-mid);
  margin-top: 8px;
}

.nw .nw-outputs {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 14px;
  margin: 6px 0 20px;
}
.nw .nw-output {
  border-radius: 10px;
  border: 1.5px solid var(--grey-pale);
  padding: 16px 18px;
  background: var(--grey-tint);
}
.nw .nw-output .code {
  display: inline-block;
  font-size: 12px;
  font-weight: 700;
  padding: 3px 10px;
  border-radius: 20px;
  border: 1.5px solid;
  margin-bottom: 8px;
}
.nw .nw-output.blue .code   { background: var(--blue-tint);   border-color: var(--blue-pale);   color: var(--blue); }
.nw .nw-output.green .code  { background: var(--green-tint);  border-color: var(--green-pale);  color: var(--green); }
.nw .nw-output.yellow .code { background: var(--yellow-tint); border-color: var(--yellow-pale); color: #A87A00; }
.nw .nw-output p {
  font-size: 13.5px;
  line-height: 1.6;
  margin: 0;
}

.nw .nw-divider {
  height: 1px;
  background: var(--grey-pale);
  margin: 32px 0;
}

.nw .nw-bio {
  display: flex;
  gap: 18px;
  align-items: flex-start;
  background: var(--blue-tint);
  border: 1.5px solid var(--blue-pale);
  border-left: 4px solid var(--blue);
  border-radius: 10px;
  padding: 20px 22px;
  margin-bottom: 20px;
}
.nw .nw-bio .bio-label {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.13em;
  text-transform: uppercase;
  color: var(--blue);
  margin-bottom: 6px;
}
.nw .nw-bio .bio-name {
  font-size: 17px;
  font-weight: 700;
  color: var(--ink);
}
.nw .nw-bio .bio-role {
  font-size: 13.5px;
  font-weight: 600;
  color: var(--blue);
  margin-bottom: 10px;
}
.nw .nw-bio p {
  font-size: 14px;
  line-height: 1.7;
}

.nw .nw-disclaimer {
  font-size: 12.5px;
  color: var(--grey-mid);
  line-height: 1.6;
  background: var(--grey-tint);
  border-radius: 8px;
  padding: 14px 18px;
}

@media (max-width: 650px) {
  .nw .nw-outputs { grid-template-columns: 1fr; }
}
</style>

<div class="nw">

  <div class="nw-label">Guest Blog</div>

  <h1 class="nw-title">When Pilots Become Infrastructure</h1>
  <div class="nw-subtitle">What Standards Deliver for European Local Digital Twins</div>

  <div class="nw-meta">
    <div class="nw-meta-pill date">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
      7 October 2026
    </div>
    <div class="nw-meta-pill author">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
      Monika Heyder, OASC
    </div>
  </div>

  <p class="nw-source">Originally published on <a href="https://monikaheyder.substack.com/p/when-the-pilots-become-infrastructure" target="_blank" rel="noopener">Substack</a> on 28 September 2026.</p>

  <p class="nw-intro">Europe’s local digital twins are moving beyond isolated pilots towards shared infrastructure and AI-enabled services. This transition creates a need for interoperability. Drawing on earlier reviews and ongoing work in ETSI STF 704, this article considers what a common European interoperability layer should enable and why institutional agency must remain part of the discussion.</p>

  <div class="nw-body">

    <h2>From projects to infrastructure</h2>

    <p>Over the past decade, European and national funding programmes, including Horizon 2020 and Horizon Europe, have supported research, experimentation and locally anchored applications of local digital twins. The resulting solutions often evolved separately, shaped by the objectives, partnerships and technical environments of individual projects. Yet this experimentation served an important purpose. Cities and regions became familiar with digital twins and gained a clearer understanding of the conditions needed for implementation: effective data governance, consolidated infrastructure and cooperation between departments. Shared use cases allowed cross-departmental exploration of how simulation, visualisation and other data-enabled tools can aid urban planning, climate action, mobility, energy management and public participation. Many projects produced valuable tools and experience, but their continued use often remained tied to a particular funding programme, consortium or technology provider.</p>

    <p>Coordination is now the next step and a significant implementation challenge. The Digital Europe Programme supports two complementary initiatives. The <a href="https://regions-and-cities.ec.europa.eu/cities-portal/eu-initiatives-cities/eu-local-digital-twin-ldt-toolbox_en" target="_blank" rel="noopener">EU Local Digital Twin Toolbox</a> intended to provide reusable technical components, while Local Digital Twins for Smart and Sustainable Communities (LDT4SSC) supports the interconnection of existing local digital twins, the creation of new ones and the development of AI-enabled capabilities across borders.</p>

    <p>These initiatives can contribute to the <a href="https://ldtcitiverse-edic.eu/" target="_blank" rel="noopener">LDT CitiVERSE European Digital Infrastructure Consortium (EDIC)</a>, which provides a structure for Member States to pool resources and connect local digital twins across Europe. Together, they signal a move from experimentation towards shared infrastructure. That infrastructure will not be created by common technical building blocks alone. Its value depends on whether existing capabilities can be connected, reused, maintained and governed across cities, regions and national borders.</p>

    <p>In June 2026, the LDT CitiVERSE EDIC described this development as a transition <a href="https://ldtcitiverse-edic.eu/eu-ldt-toolbox-launch-box/" target="_blank" rel="noopener">“from project to European public infrastructure.”</a> This shift brings a different set of questions: Which elements require common agreement, and where should different approaches remain possible? Can cities benefit from shared infrastructure without becoming dependent on a single architecture, provider or implementation model? Can locally developed systems work together? What can standards contribute while preserving local technological and institutional choice?</p>

    <figure class="nw-figure">
      <img src="https://ldt4ssc.eu/images/substack.png" alt="Illustration accompanying the article When Pilots Become Infrastructure">
      <figcaption>© Monika Heyder</figcaption>
    </figure>

    <h2>Local Digital Twin - more than a digital model</h2>

    <p>A local digital twin is sometimes understood primarily as a three-dimensional representation of a city. Such representations can be useful, but they capture only part of its potential. In practice, a local digital twin can integrate and orchestrate data, models, services and administrative processes. It brings together information from otherwise disconnected urban systems—including mobility, buildings, energy networks, environmental sensors and planning processes—to support decisions across organisational and sectoral boundaries.</p>

    <p>The requirements therefore extend well beyond accurate representation. A digital twin should accommodate changing data sources, analytical tools, services and, crucially, users across the organisation. Its outputs should be technically accessible, sufficiently reliable for their intended purpose and understandable enough to be used, questioned and debated.</p>

    <p>Provided to cities the twin can give departments a common point of reference, support assessments and strengthen an administration’s position with contractors and service providers. Its value lies not only in the answers it produces, but in enabling informed discussion about which solution is appropriate for a particular public task.</p>

    <p>However, cities and their digital infrastructures are constantly changing, and the twin is only one component of that wider environment. Therefore, it must remain functional in the face of constant change: applications and sensors are added, services are discontinued, requirements change or suppliers are replaced. Maintaining quality, continuity and intelligibility through these changes is a central implementation challenge.</p>

    <p>The earlier work of the <a href="https://zenodo.org/records/17799223" target="_blank" rel="noopener">CEN/TC 465 Ad Hoc Group on Climate-Neutral and Smart Cities and Communities</a> highlighted this challenge. The experts and examples clearly highlighted that while technical solutions exist in many areas, fragmented data environments, limited organisational capacity and a lack of common implementation mechanisms restrict their transfer and wider use. Central is for the implementation to remain usable, adaptable and governable over time. Interoperability is central to that question.</p>

    <h2>Interoperability as an enabler</h2>

    <p>Interoperability is often presented as a technical property: systems can exchange data, connect through common interfaces or interpret shared information models. For a public administration, however, its practical meaning is wider. Interoperability affects whether a solution developed for one service or territory can be reused elsewhere, whether components from different providers can be combined and whether an administration can change direction without rebuilding the entire system.</p>

    <p>Interoperability is not technological uniformity. European cities and communities differ considerably regarding infrastructure, institutional organisation and digital maturity. The integration of new technologies has to accommodate legacy systems. One single European solution would be unlikely to meet these different needs, and requiring identical technologies would be neither realistic nor desirable. Consequences could concentrate dependencies and common vulnerabilities across otherwise diverse systems.</p>

    <p>European interoperability initiatives have consequently focused on establishing a minimum common layer: one that defines the capabilities and requirements necessary for cooperation while allowing different technical mechanisms to fulfil them. The <a href="https://mims.oascities.org/" target="_blank" rel="noopener">Minimal Interoperability Mechanisms</a> (MIMs) can provide such a layer. They specify what participating systems need to achieve—for example, how data is made available, how context information is described or how access is governed—without prescribing a complete technical stack. A reference architecture can complement them by clarifying the principal components, functions and relationships within an ecosystem.</p>

    <p>Properly designed, these instruments do more than connect systems. They create conditions for transferability, modular procurement and technological choice. This is what <a href="https://oascities.org/minimal-interoperability-mechanisms/" target="_blank" rel="noopener">Open &amp; Agile Smart Cities and Communities (OASC) and its members have been working towards</a>, supported by European initiatives including Living-in.EU. More recently, the relationship between MIMs and local digital twins has received renewed institutional attention through European standardisation.</p>

    <h2>The contribution of ETSI STF 704</h2>

    <p>Here <a href="https://portal.etsi.org/xtfs/#/xTF/704/what-we-do" target="_blank" rel="noopener">ETSI Specialist Task Force 704</a> enters the picture. Responding to priorities identified in the <a href="https://interoperable-europe.ec.europa.eu/collection/rolling-plan-ict-standardisation" target="_blank" rel="noopener">Rolling Plan for ICT Standardisation</a> and <a href="https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:C_202501818" target="_blank" rel="noopener">Action 17 of the 2025 Annual Union Work Programme for European Standardisation</a>, the Task Force is developing standards and implementation guidance for interoperable and AI-enabled local digital twins. It is funded by the European Union under the Single Market Programme (SMP-STAND-2025-ESOS-01-IBA Topic 20). The work covers a reference architecture for AI-enabled local digital twins, Minimal Interoperability Mechanisms and practical guidance for applying the formal standards. The MIMs framework itself builds on several years of collaborative development and has evolved through successive releases. <a href="https://mims.oascities.org/mims-plus-specification-9.0" target="_blank" rel="noopener">Version 9.0</a> underwent an open review process in 2026 following substantial changes to its structure and specifications.</p>

    <p>The planned outputs address three related needs. EN 304 181 develops a reference architecture for AI-enabled local digital twins. EN 304 182 covers MIMs 0, 1, 2 and 7, addressing the common MIM framework, context information management, shared data models and geospatial information. TR 104 183 provides a practical companion to the two standards, helping stakeholders understand the framework and apply it through use cases and migration guidance.</p>

    <div class="nw-outputs">
      <div class="nw-output blue">
        <span class="code">EN 304 181</span>
        <p>Reference architecture for AI-enabled local digital twins</p>
      </div>
      <div class="nw-output green">
        <span class="code">EN 304 182</span>
        <p>MIMs 0, 1, 2 and 7: common MIM framework, context information management, shared data models and geospatial information</p>
      </div>
      <div class="nw-output yellow">
        <span class="code">TR 104 183</span>
        <p>Practical companion: use cases and migration guidance</p>
      </div>
    </div>

    <p>Each output performs a distinct function. The reference architecture establishes a common understanding of the components of a local digital twin and the relationships between them. The MIM standard identifies the capabilities and requirements needed for different systems to work together. The implementation guidance helps organisations combine and apply these elements in different technical and institutional settings. Together, they aim to provide a shared foundation without requiring every city, community or provider to adopt the same complete solution.</p>

    <p>These outputs build on work undertaken through the OASC MIM working groups and seek alignment with European initiatives including the <a href="https://ldtcitiverse-edic.eu/" target="_blank" rel="noopener">LDT CitiVERSE EDIC</a>, the EU Local Digital Twin Toolbox and the <a href="https://spec.knows.idlab.ugent.be/ldt-interoperability-blueprint/v1/" target="_blank" rel="noopener">interoperability blueprint</a> developed through LDT4SSC. Relevant work from other standardisation activities is being considered, including the German specification <a href="https://www.dinmedia.de/en/technical-rule/din-spec-91607/384414386" target="_blank" rel="noopener">DIN SPEC 91607</a> on digital twins for cities and municipalities.</p>

    <p>Building on existing work is not sufficient. The group also needs input from cities, industry representatives and other stakeholders with strategic and implementation experience. Interoperability requirements cannot be defined solely from the perspective of technical architecture. They must also reflect how local and regional governments procure technology, organise responsibilities, govern data and integrate digital tools into public services.</p>

    <p>A session with the LDT4SSC Stakeholder Forum is scheduled for 14 October 2026. Expert interviews will provide further input towards workshops planned for January 2027, where the draft documents can be discussed in greater depth. Together, these activities create several routes through which practical implementation knowledge can inform the standards. This is particularly valuable for public authorities and other stakeholders that have relevant experience but lack the resources to participate continuously in formal technical committees.</p>

    <h2>AI-enabled</h2>

    <p>AI is becoming part of local digital twin development. It may extend a digital twin from monitoring and simulation towards prediction, faster scenario generation, recommendations and, potentially, more automated orchestration of services and processes. Emissions modelling provides one example. In suitable applications AI may accelerate parts of the analysis or produce approximate results at a lower computational cost, allowing a wider range of scenarios to be explored. Rather than replacing established models, they may provide complementary inputs that can be assessed alongside them. ETSI STF 704 will explore different approaches in the course of the drafting process in 2026 and 2027.</p>

    <p>Additionally the STF 704 considers where AI fits within the local digital twin architecture. As many applications are still developing, the architecture should accommodate AI without assuming a single mature pattern of use. Technical capability does not transfer institutional responsibility. Decisions about whether and how AI should be used remain connected to context, public values and the responsible organisation’s ability to understand and challenge the system.</p>

    <h2>Shared infrastructure and local agency</h2>

    <p>Shared European infrastructure can help address a problem that individual cities cannot solve alone. Few local or regional governments have the resources to develop and maintain every component of a sophisticated local digital twin ecosystem independently. Common specifications, reusable components and pooled expertise can reduce duplication and make advanced capabilities available to a wider range of administrations.</p>

    <p>Yet sharing infrastructure should not mean transferring responsibility or control elsewhere. Digital agency in this context does not require every administration to become technologically self-sufficient. It means retaining meaningful choices over data, infrastructure, models and providers. A city should be able to understand what a system does, determine how it is used, combine components from different sources and replace them when necessary.</p>

    <p>Whichever implementation model decision-makers choose—building, buying, outsourcing or sharing—it should be grounded in a common vision that serves the organisation as a whole. Early scoping should clarify the twin’s public purpose, intended users and decision processes, allocation of responsibilities and acceptable dependencies. This groundwork enables successful experiments to mature into dependable infrastructure rather than accumulate as disconnected use cases.</p>

    <p>Interoperability contributes to institutional agency only when organisations can exercise the choices it creates. Public buyers still need the capacity to translate interoperability requirements into procurement, assess supplier claims and govern the resulting systems throughout their lifecycle. Smaller administrations may require shared procurement arrangements, technical assistance and support from intermediary organisations. Common infrastructure can widen the range of available choices, but organisational capability determines whether public administrations can make meaningful use of them.</p>

    <h2>Conclusion</h2>

    <p>The next phase of Europe’s local digital twin development will not be defined only by more advanced models or larger volumes of data. The ability to turn project results into infrastructure that can be shared, maintained and governed over time will be decisive—not least for ensuring that public investment continues to create value beyond the original funding period.</p>

    <p>LDT4SSC provides an environment for testing interconnection and deployment. The LDT CitiVERSE EDIC can provide institutional continuity at European level, while the specifications developed through ETSI STF 704 can establish a common foundation for connecting different systems, components and approaches. These roles are complementary: practical deployment, shared governance and standardisation each contribute to infrastructure that can operate across organisational and territorial boundaries.</p>

    <p>The choice is not between European standardisation, national programmes and local diversity. These levels need to reinforce one another. European standards can provide a common foundation. National and regional programmes can recognise it in their funding conditions and support its implementation. Local and regional governments can translate relevant interoperability requirements into procurement and governance arrangements suited to their needs.</p>

    <p>ETSI STF 704 can make an important contribution, but its impact will depend on whether the resulting standards are recognised and used. Their success should be judged not by their publication, but whether they ease the work of cities and communities in regards to reuse solutions, cooperate across organisational and territorial boundaries and benefit from a shared European ecosystem while retaining the authority and capacity to shape their own digital transformation.</p>

  </div>

  <div class="nw-divider"></div>

  <div class="nw-bio">
    <div>
      <div class="bio-label">About the author</div>
      <div class="bio-name">Monika Heyder</div>
      <div class="bio-role">Senior Advisor on Standardisation, OASC</div>
      <p>Monika Heyder works at the intersection of urban sustainability, digitalisation and global policy. With more than 15 years of experience leading transformation projects across Europe, she helps cities and organisations turn local innovation into frameworks that scale — through standards, strategy and structured knowledge exchange.</p>
    </div>
  </div>

  <p class="nw-disclaimer">This is a guest contribution. The views and opinions expressed in this article are those of the author and do not necessarily reflect the position of the LDT4SSC consortium, the European Union or the European Commission.</p>

</div>
