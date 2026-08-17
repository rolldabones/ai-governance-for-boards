# Jurisdiction Guide: Vietnam

**Status: current as at 13 August 2026 (KST); commencement of Decision No. 33/2026/QD-TTg re-checked as at 17 August 2026 (KST). Vietnam's AI Law is in force with transitional periods running. The high-risk list is no longer pending: it issued as Decision No. 33/2026/QD-TTg on 30 June 2026 and took effect on 15 August 2026. The penalty schedule remains outstanding. Verify current status before relying on anything below.**

> **Amendment note, 13 August 2026 (KST).** This guide previously described the high-risk list as pending. That posture was accurate when written and expired on 15 August 2026. The list, its criteria and its transition timetable are restated below. Verification particulars and the one residual gap are recorded at the end of this guide.

## Regulatory approach

Vietnam enacted the first standalone, binding AI statute in Southeast Asia: the Law on Artificial Intelligence, No. 134/2025/QH15, passed by the National Assembly on 10 December 2025 and effective 1 March 2026. The law consolidates the AI provisions previously embedded in the Law on Digital Technology Industry (No. 71/2025/QH15) into a single framework of eight chapters and thirty-five articles covering research, development, provision, deployment and use of AI systems, the rights and obligations of participants and state management. The Ministry of Science and Technology leads enforcement, and a National AI Committee was mandated for establishment by 1 July 2026.

The architecture is recognizably EU-influenced, risk-based with role-driven obligations and transparency duties, but with distinctive Vietnamese emphases: data sovereignty, national AI self-reliance, cultural values and an explicit statutory philosophy of human-centricity. The law states in terms that AI serves humans, does not replace humans and that humans retain oversight of important decisions. AI systems used exclusively for national defense, security or cryptography are carved out to specialized legislation. The law applies to Vietnamese and foreign organizations and individuals participating in AI activities in Vietnam, including foreign providers whose systems reach Vietnamese users, such as SaaS platforms.

## Risk classification

Article 9 classifies AI systems into three tiers, high, medium and low risk, by potential impact on human life, health, lawful rights and interests, public interests and social order. Two structural points matter for planning. First, unlike the EU's exhaustive annexes, the detailed high-risk list is delegated to the Prime Minister, so scope can move by sub-legal instrument. That delegation has now been exercised: Decision No. 33/2026/QD-TTg, set out in the next section, issued the list and took effect on 15 August 2026. Second, classification is a precondition of operation: the first implementing decree, Decree 142/2026/ND-CP (issued 30 April 2026, effective 1 May 2026), requires risk classification before a system is put into operation, by self-assessment or by a conformity assessment body, with the managing agency able to require independent assessment for high-risk systems. Providers classify systems (foundation models are treated separately), and deployers must coordinate reclassification when changes in function or intended use create new risks, which means organizations integrating third-party model APIs can trigger reclassification through integration choices alone.

## The high-risk list: Decision No. 33/2026/QD-TTg

*[Binding law. Pinpoint: Decision No. 33/2026/QD-TTg. As at 13 August 2026 (KST).]*

Decision No. 33/2026/QD-TTg was issued 30 June 2026 by the Prime Minister and signed by Deputy Prime Minister Ho Quoc Dung. It took effect on **15 August 2026**.

**Framing principles.** The Decision provides that AI systems must meet the basic operating principles of the AI Law; that the use of an AI system **does not change, transfer or exclude the authority and responsibility of the competent body, organization or individual**; that human supervision, control and the ability to intervene must be assured during operation; and that prohibited acts must not be performed.

**Determination criteria.** A system is high-risk where it may cause significant damage to life, health, the lawful rights and interests of organizations and individuals, the national interest, the public interest or national security, per Article 9 of the AI Law and Article 8(1) of Decree No. 142/2026/ND-CP, and where it is not excluded under Article 8(2) of that Decree.

**The six listed domains.**

| Domain | Listed systems |
|---|---|
| Education | Self-study content delivery drawing on uncontrolled data sources; automated testing, evaluation and ranking of learners; monitoring and analysis of learner behavior |
| Ethnicity and religion | Automated scoring, classification and ranking of dossiers to determine policy beneficiaries and areas; automated authentication and validity determinations on ethnicity and religion information; automated approval or refusal of registration, renewal or cancellation in state management |
| Health | Surgical support systems and surgical robots, including robotic equipment under automated AI control |
| Banking | Automated execution of electronic transactions in banking activity; automated credit-granting decisions |
| Litigation | Wide-scale biometric identification systems serving the resolution of public-interest civil cases |
| Transport | 31 systems, including high-level autonomous driving control on vehicles; automated control of road and rail signaling and traffic dispatch; operation and control of critical transport works and technical infrastructure |

**Read the litigation entry narrowly.** The listed system is wide-scale biometric identification in public-interest civil proceedings. The Decision does not enumerate legal services generally, and a board that reads "litigation" as capturing contract review, research or advisory tooling will over-scope its obligations. Compare the equivalent point under Colorado SB 26-189 in the [United States guide](us.md), where legal services is likewise not an enumerated covered domain.

## Key obligations

- **Generative AI.** Providers must disclose the data sources used to train models and apply digital watermarks to AI-generated content, addressing provenance and misinformation concerns directly in statute.
- **High-risk systems.** Conformity requirements, potential pre-use certification, incident reporting and human oversight obligations, with detail continuing to arrive by decree. Foreign providers of high-risk systems must establish a local contact point, and systems requiring pre-use conformity certification may need a commercial presence or authorized representative.
- **Prohibited acts.** Article 7 prohibits, among other things, exploiting or hijacking AI systems to commit illegal acts or infringe lawful rights and interests.
- **Penalties.** Calculated as a percentage of global revenue on the model of Vietnam's data protection regime, with specific amounts to be set by decree. The design signals proportionate reach to large foreign operators; the pending schedule is a watch item, not a reason to defer compliance.
- **Sandbox.** A regulatory sandbox permits supervised testing of high-risk AI products with transition to full compliance on exit, coexisting with the general digital technology sandbox under Decree 353/2025/ND-CP; an AI startup can fall under both regimes depending on product scope.

## Transition timetable

Systems already in operation before 1 March 2026 may continue operating during transition if not causing serious risks, subject to a notification duty: under Decree 142/2026/ND-CP, transitioning organizations had to submit notice within 60 days of the decree's effect, by end of June 2026. Substantive compliance is then phased by sector: most businesses must comply by 1 March 2027, with healthcare, education and finance extended to 1 September 2027.

Decision No. 33/2026/QD-TTg carries its own transition for listed systems **already in operation before 15 August 2026**: providers and deployers must complete their compliance obligations before **1 September 2027** for health, education and finance systems, and before **1 March 2027** for the remaining listed domains. During the transition those systems may continue to operate, unless a competent state authority determines that a system risks causing serious damage and requires suspension or termination under Article 35(2) of the AI Law. Note the asymmetry: the Decision's transition runs from the list's effective date, not the AI Law's, so a system that entered service between 1 March and 15 August 2026 sits inside both regimes. Boards should read the sector extension correctly: the highest-stakes sectors received more time because their obligations are heaviest, not lightest.

## The surrounding stack

The AI Law operates alongside a fast-built adjacent framework that AI deployments trigger simultaneously: the Law on Personal Data Protection (No. 91/2025/QH15, effective 1 January 2026), which applies to every AI system processing personal data and carries its own global-revenue-based penalties; the data law governing cross-border transfer of important data with impact assessment and breach notification duties; and cybersecurity law retaining data localization requirements for specified categories including account, usage, payment and IP address data. Compliance planning for AI in Vietnam is a three-body problem at minimum; treating the AI Law alone as the perimeter is the characteristic foreign-entrant error.

## Board priorities in Vietnam

1. **Classify before operating, and re-classify on change.** The pre-operation classification duty is the gating control, and integration or feature changes can re-trigger it. Build classification into the deployment gate rather than treating it as an annual review item.
2. **Run the register against the issued list, and do not wait on the penalty schedule.** The high-risk list is no longer a watch item; it has been in force since 15 August 2026 and every system should be tested against the six domains now. The penalty schedule remains outstanding, and waiting for it before acting is itself a compliance risk given the March and September 2027 deadlines.
3. **Generative AI provenance is statutory.** Training data source disclosure and output watermarking are binding duties, converging with Korea's labeling regime and the EU's Article 50 obligations; a single provenance architecture can serve all three.
4. **Structure the local presence early.** Contact point, possible authorized representative and data localization questions interact; the corporate structuring decision is slower than the compliance decision and should lead it.
5. **Integrate with PDPL compliance.** The AI Law and the personal data protection law overlap on any system touching personal data; a coordinated program avoids duplicated assessments and contradictory positions.

## Doctrine mapping

Vietnam wrote this handbook's first doctrine pairing into its statute more explicitly than any other jurisdiction covered here: the human-centricity principle, that humans retain oversight of important decisions and AI does not replace human authority and responsibility, is [Final Liability](../01-doctrine/final-liability.md) as legislative text. Decision No. 33/2026/QD-TTg restates the point in sharper terms still, providing that the use of an AI system does not change, transfer or exclude the authority and responsibility of the competent body, organization or individual. That is the doctrine in operative regulatory language: deploying the system moves no liability off the person who already held it. The pre-operation classification and conformity discipline is [Informed Intent](../01-doctrine/informed-intent.md): authorization precedes action. And the transition regime's tolerance for continued operation only where systems are not causing serious risk is a statutory expression of [Slow AI](../01-doctrine/slow-ai.md): the right to operate follows from being governable.

## Verification particulars

*[As at 13 August 2026 (KST).]*

Decision No. 33/2026/QD-TTg was verified against the official gazette record of the Government Portal (vanban.chinhphu.vn), which confirms the number, issuing body, issue date of 30 June 2026, effective date of 15 August 2026, signatory and official title, and carries the signed instrument as an attached PDF. The framing principles, determination criteria, domain list and transition timetable are taken from the Government's own e-newspaper, Bao Dien tu Chinh phu, reporting the Decision on 2 July 2026.

⧉ **Residual gap.** The signed PDF of the Decision is not machine-readable, so the itemised annex was not read line by line from the instrument itself. The transport domain in particular is reported as comprising 31 systems, of which only three are named here. A board operating transport, rail or critical-infrastructure AI should obtain the full annex before scoping. Decree No. 142/2026/ND-CP is cited above for its Article 8 criteria and exclusions on the same basis.

---

**Final Liability rests with the Human.**
