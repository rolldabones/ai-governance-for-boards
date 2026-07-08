# Global Best Practices

**Twelve practices that hold in every jurisdiction this handbook covers, and in the jurisdictions it does not. Where local law adds prescription, these are the substrate it adds it to.**

The regulatory regimes of the EU, the US, Korea, Vietnam and Australia differ in instrument, philosophy and enforcement posture, and they converge on the same operational demands. The practices below are the convergence set. An organization that operates all twelve carries the operational substrate that every covered regime builds on, leaving jurisdiction-specific compliance as configuration rather than construction, and is positioned to absorb new regulation at low marginal cost. That is the [Slow AI](../01-doctrine/slow-ai.md) argument for building governance once, well. The practices are not a substitute for jurisdiction-specific legal analysis; they are what makes that analysis implementable.

## 1. Maintain a living AI register

A consolidated record of every AI system in use, including embedded vendor functionality and known shadow use, with purpose, named owner, risk classification, data dependencies, vendor and review date. Every jurisdiction's regime presupposes it: EU and Vietnamese risk classification, Korean category determinations, Australian and US automated decision-making disclosures all begin with knowing what is running. Refresh on a schedule and on trigger events.

## 2. Name the humans

A named senior executive accountable for AI governance, named system owners across each system's lifecycle from design to decommissioning and named decision owners for consequential outcomes, all recorded in the register and reflected in position descriptions, delegations and incentives. This is [Final Liability](../01-doctrine/final-liability.md), and it is also the first question every regulator asks after an incident.

## 3. Set a differentiated risk appetite

A board-approved AI risk appetite differentiated by technology category, stakeholder exposure, decision consequence and reversibility, cascaded into the risk management framework and the approval gates. Statements of AI values sit alongside it to answer the lawful-but-unwise cases regulation has not reached.

## 4. Gate deployment with authorization

No material AI system enters operation without documented approval recording purpose, scope, classification, owner and exit; no agentic system enters operation without a full [Informed Intent](../01-doctrine/informed-intent.md) instrument covering purpose, scope of action, authority, human checkpoints and a tested exit. Re-authorization triggers on change of scope, model, vendor or integration.

## 5. Classify by risk, everywhere

Risk-classify every system against the strictest framework the organization faces, and record the classification per jurisdiction in the register. The classifications differ in detail (EU Annex III, Korea's high-impact categories, Vietnam's three tiers, US state consequential-decision definitions) but overlap heavily in substance: employment, credit, healthcare, education, essential services and safety-relevant uses are high-stakes everywhere.

## 6. Keep humans over consequential decisions

Meaningful human oversight, with real ability to intervene, over any AI-informed decision with legal or similarly significant effect on a person, and the capacity to explain such decisions to the person affected. This single practice discharges obligations in all five jurisdiction guides simultaneously and is the practical core of Final Liability.

## 7. Be transparent about AI and its outputs

Tell people when they are interacting with AI. Label or watermark synthetic content, using machine-readable provenance standards where feasible. Disclose automated decision-making in privacy notices where required. Korea, Vietnam, the EU and multiple US states have made versions of this statutory; one provenance and disclosure architecture serves all of them.

## 8. Extend cyber and data governance into AI explicitly

Rapid patching and privileged access management inside AI environments, data classification and lifecycle management underneath AI deployment, unified logging and monitoring across cyber, model and data incidents. AI governance fails wherever data governance and cyber security are weak, and supervisory guidance across jurisdictions now says so in near-identical language.

## 9. Manage the vendor layer as the primary risk channel

Due diligence and pre-adoption testing against appetite, visibility of vendor ownership, location and fourth-party cloud concentration, contractual incident notification, reporting, audit and testing rights, fallback arrangements and a costed exit. Accountability for vendor-originated failure never leaves the organization.

## 10. Govern shadow AI by provision, then policy, then policing

An acceptable use policy, sanctioned tools that give staff a compliant alternative, training on confidentiality and hallucination risk and network-level monitoring, in that order. Prohibition without provision fails everywhere it has been tried.

## 11. Assure, independently and proportionately

Independent verification of control effectiveness, scaled to stakes: full external assurance for high-stakes estates, targeted testing (for example, how sensitive datasets are used inside internal AI systems) for smaller ones, AI on the internal audit plan for everyone. Documentation retained to the longest applicable standard; Korea's five-year retention is a serviceable global default.

## 12. Measure value with the same rigor as risk

Use-case-level ROI with metrics set before investment, phase-appropriate evaluation, full cost modeling including consumption pricing and a demonstrated willingness to retire what underperforms. See [Measuring AI value](../04-value-and-returns/measuring-ai-value.md). Value discipline is a governance practice because ungoverned spend and ungoverned risk are the same culture.

## Using this list

The twelve practices are sequenced deliberately: the register enables the naming, the naming enables the appetite, the appetite enables the gates and everything downstream operates on what the first four establish. An organization starting from zero should build in order and resist the temptation to begin with the practice its favorite vendor sells. For per-jurisdiction additions, see the [jurisdiction guides](../05-jurisdictions/); for the interrogation layer, see the [board questions bank](board-questions.md) and [red flags](red-flags.md).

---

**Final Liability rests with the Human.**
