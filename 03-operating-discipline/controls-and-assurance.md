# Controls and Assurance

**The board oversees a comprehensive process to identify AI risks, match them with controls, verify the controls work and repeat as the technology and threat environment move.**

## Risk management inside the existing framework

For most organizations, AI risk identification and management belongs inside the existing enterprise risk management framework, aligned to the board's AI risk appetite, rather than in a parallel structure. AI adds risks and sharpens existing ones; it does not need a second risk universe. What it does need is explicit presence: an ERM framework that never mentions AI, or a risk register with no process to assess any AI-enabled application, is the baseline red flag.

Controls are then selected by factors familiar from every other risk domain: the type of AI, the use case, the nature and severity of the risk, the appetite and the operating context. Both risks and controls are reviewed on a cycle that matches the technology's pace, which currently means at least annually with event-driven triggers, not annually alone.

## The core policy instruments

### The AI inventory or register

The register tracks all approved AI systems and tools with key information about each: purpose, owner (the named human of [Final Liability](../01-doctrine/final-liability.md)), risk classification, data dependencies, vendor, approval date and review date. It is the board's single view of AI across the organization and the artifact every jurisdiction guide in this handbook ultimately presupposes: risk classification duties in the EU and Vietnam, high-impact determinations in Korea, automated decision-making disclosures in Australia and US states all begin with knowing what is running. As AI features embed inside broader platforms, the register should capture embedded functionality, not just standalone systems, and there must be a process that keeps it current. A register is a snapshot with a refresh process; without the process it is a souvenir.

### The AI policy

The central policy document setting the rules and processes for AI use across the organization: which systems are approved, the rules applying to them, which are prohibited and how new use cases enter the approved list. In some organizations the staff-facing rules live in a separate acceptable use policy. The policy is owned by the senior manager accountable for AI and approved at a level matching the organization's size and complexity. Public-sector AI policy templates now exist in several jurisdictions and are serviceable starting points; the customization that matters is the mapping to the organization's own register, appetite and named owners.

## A control catalog boards should recognize

The board does not select controls, but it should recognize whether the catalog management presents is complete. A serviceable baseline, by risk area:

| Risk area | Common controls |
|---|---|
| Cyber security | Rapid patching inside AI environments; existing controls (encryption, access control, monitoring, incident response) explicitly extended to AI-specific risks; AI threat modeling, red-teaming and penetration testing |
| Privacy | Privacy impact assessments for AI systems; privacy policies and notices updated for AI-specific data practices, including automated decision-making disclosures where required; data security across the AI lifecycle |
| Output quality | Model testing, validation and fine-tuning; staff training on limitations; human review of outputs in high-stakes contexts |
| Explainability | Documentation of model design, inputs and intended use; processes for explaining AI-driven decisions to affected individuals |
| Fairness | Representativeness and quality assessment of training data; bias testing across protected attributes; AI impact assessments |
| Shadow AI | Acceptable use policy; approved-tool provisioning; staff training on risks and obligations; monitoring of AI use across networks |
| Agentic AI | Documented risk appetite for what tasks agents may perform; access controls limiting what agents can read, modify and action; logging and auditability of agent actions; tested suspension and exit ([Informed Intent](../01-doctrine/informed-intent.md)) |
| Vendor | Due diligence and pre-adoption testing consistent with appetite; visibility of vendor location, ownership and fourth-party cloud dependencies; contractual incident notification, reporting and testing rights; fallback arrangements |

## Vendors: the four-step oversight loop

Because most AI risk enters through vendors, board oversight of the vendor layer deserves its own loop: (1) understand what testing and trialing of the vendor's product occurred before adoption and whether results sit inside appetite; (2) understand the provider's location and ownership structure, its interdependencies with other infrastructure providers and the fallback available on system failure; (3) monitor the provider's data governance and security posture on an ongoing basis; (4) confirm performance and data security are reflected in contract: reporting duties, incident notification and rights to undertake testing. Information flow diagrams mapping how data moves between the organization and AI systems, with the internal and external access points and controls at each, are a compact tool supporting both this loop and board comprehension generally.

## Assurance

The board should have confidence, not hope, that AI risks are controlled, which means assurance in the audit sense: independent verification of control effectiveness. External assurance brings objectivity and specialized expertise internal teams may lack, and increasingly cuts across cyber security and data governance simultaneously because the underlying systems are interconnected. Internal audit's AI coverage should be on the audit plan explicitly. Smaller organizations can buy assurance in targeted, cost-effective slices, for example independent testing of how sensitive datasets are used within internal AI systems, rather than full-scope engagements. The assurance principle mirrors the accountability principle: verification can be outsourced; the obligation to be verifiable cannot.

## The cyber and data governance junction

Cyber security recurs across every survey as the AI risk boards worry about most, and rightly, because AI risk is structurally interconnected with cyber resilience and data governance. Three synergies worth the board's attention: data classification and lifecycle management underpin both least-privilege security and safe AI deployment; strong cyber controls (secure configuration, vulnerability testing, third-party risk management) apply equally to AI workflows, including AI-generated code and agentic systems; and unified data inventories, logging and monitoring enable faster detection of cyber incidents, model failures and breaches together, with coordinated response, regulatory reporting and board oversight downstream. Boards that already run mature cyber and data governance oversight should extend those mechanisms to AI explicitly rather than building a third silo.

## Board questions for this element

1. What steps give us confidence we are meeting legal and regulatory obligations for AI and the associated data collection, storage and use?
2. Does the risk management framework adequately address AI-related risks, and does it differentiate high-risk from low-risk applications?
3. What controls govern agentic risk, and have the suspension mechanisms been tested?
4. Do our privacy, data governance, cyber and procurement policies address AI, and when were they last reviewed for it?

---

**Final Liability rests with the Human.**
