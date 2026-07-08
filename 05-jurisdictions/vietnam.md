# Jurisdiction Guide: Vietnam

**Status: current as at early July 2026. Vietnam's AI Law is in force with transitional periods running; the first implementing decree has issued and further decrees, including the high-risk list and penalty schedule, are pending. Verify current status before relying on anything below.**

## Regulatory approach

Vietnam enacted the first standalone, binding AI statute in Southeast Asia: the Law on Artificial Intelligence, No. 134/2025/QH15, passed by the National Assembly on 10 December 2025 and effective 1 March 2026. The law consolidates the AI provisions previously embedded in the Law on Digital Technology Industry (No. 71/2025/QH15) into a single framework of eight chapters and thirty-five articles covering research, development, provision, deployment and use of AI systems, the rights and obligations of participants and state management. The Ministry of Science and Technology leads enforcement, and a National AI Committee was mandated for establishment by 1 July 2026.

The architecture is recognizably EU-influenced, risk-based with role-driven obligations and transparency duties, but with distinctive Vietnamese emphases: data sovereignty, national AI self-reliance, cultural values and an explicit statutory philosophy of human-centricity. The law states in terms that AI serves humans, does not replace humans and that humans retain oversight of important decisions. AI systems used exclusively for national defense, security or cryptography are carved out to specialized legislation. The law applies to Vietnamese and foreign organizations and individuals participating in AI activities in Vietnam, including foreign providers whose systems reach Vietnamese users, such as SaaS platforms.

## Risk classification

Article 9 classifies AI systems into three tiers, high, medium and low risk, by potential impact on human life, health, lawful rights and interests, public interests and social order. Two structural points matter for planning. First, unlike the EU's exhaustive annexes, the detailed high-risk list is delegated to the Prime Minister, so scope can move by sub-legal instrument; healthcare, education and finance systems are treated as high-risk by default. Second, classification is a precondition of operation: the first implementing decree, Decree 142/2026/ND-CP (issued 30 April 2026, effective 1 May 2026), requires risk classification before a system is put into operation, by self-assessment or by a conformity assessment body, with the managing agency able to require independent assessment for high-risk systems. Providers classify systems (foundation models are treated separately), and deployers must coordinate reclassification when changes in function or intended use create new risks, which means organizations integrating third-party model APIs can trigger reclassification through integration choices alone.

## Key obligations

- **Generative AI.** Providers must disclose the data sources used to train models and apply digital watermarks to AI-generated content, addressing provenance and misinformation concerns directly in statute.
- **High-risk systems.** Conformity requirements, potential pre-use certification, incident reporting and human oversight obligations, with detail continuing to arrive by decree. Foreign providers of high-risk systems must establish a local contact point, and systems requiring pre-use conformity certification may need a commercial presence or authorized representative.
- **Prohibited acts.** Article 7 prohibits, among other things, exploiting or hijacking AI systems to commit illegal acts or infringe lawful rights and interests.
- **Penalties.** Calculated as a percentage of global revenue on the model of Vietnam's data protection regime, with specific amounts to be set by decree. The design signals proportionate reach to large foreign operators; the pending schedule is a watch item, not a reason to defer compliance.
- **Sandbox.** A regulatory sandbox permits supervised testing of high-risk AI products with transition to full compliance on exit, coexisting with the general digital technology sandbox under Decree 353/2025/ND-CP; an AI startup can fall under both regimes depending on product scope.

## Transition timetable

Systems already in operation before 1 March 2026 may continue operating during transition if not causing serious risks, subject to a notification duty: under Decree 142/2026/ND-CP, transitioning organizations had to submit notice within 60 days of the decree's effect, by end of June 2026. Substantive compliance is then phased by sector: most businesses must comply by 1 March 2027, with healthcare, education and finance extended to 1 September 2027. Boards should read the sector extension correctly: the highest-stakes sectors received more time because their obligations are heaviest, not lightest.

## The surrounding stack

The AI Law operates alongside a fast-built adjacent framework that AI deployments trigger simultaneously: the Law on Personal Data Protection (No. 91/2025/QH15, effective 1 January 2026), which applies to every AI system processing personal data and carries its own global-revenue-based penalties; the data law governing cross-border transfer of important data with impact assessment and breach notification duties; and cybersecurity law retaining data localization requirements for specified categories including account, usage, payment and IP address data. Compliance planning for AI in Vietnam is a three-body problem at minimum; treating the AI Law alone as the perimeter is the characteristic foreign-entrant error.

## Board priorities in Vietnam

1. **Classify before operating, and re-classify on change.** The pre-operation classification duty is the gating control, and integration or feature changes can re-trigger it. Build classification into the deployment gate rather than treating it as an annual review item.
2. **Do not wait for the pending decrees.** The high-risk list and penalty schedule are outstanding, and waiting for them before acting is itself a compliance risk given the March and September 2027 deadlines. Classify conservatively now; adjust when the list issues.
3. **Generative AI provenance is statutory.** Training data source disclosure and output watermarking are binding duties, converging with Korea's labeling regime and the EU's Article 50 obligations; a single provenance architecture can serve all three.
4. **Structure the local presence early.** Contact point, possible authorized representative and data localization questions interact; the corporate structuring decision is slower than the compliance decision and should lead it.
5. **Integrate with PDPL compliance.** The AI Law and the personal data protection law overlap on any system touching personal data; a coordinated program avoids duplicated assessments and contradictory positions.

## Doctrine mapping

Vietnam wrote this handbook's first doctrine pairing into its statute more explicitly than any other jurisdiction covered here: the human-centricity principle, that humans retain oversight of important decisions and AI does not replace human authority and responsibility, is [Final Liability](../01-doctrine/final-liability.md) as legislative text. The pre-operation classification and conformity discipline is [Informed Intent](../01-doctrine/informed-intent.md): authorization precedes action. And the transition regime's tolerance for continued operation only where systems are not causing serious risk is a statutory expression of [Slow AI](../01-doctrine/slow-ai.md): the right to operate follows from being governable.

---

**Final Liability rests with the Human.**
