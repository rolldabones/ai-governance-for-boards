# Jurisdiction Guide: Republic of Korea

**Status: current as at early July 2026. Korea's AI Framework Act and its Enforcement Decree are in force. A grace period on administrative fines runs through the first year of enforcement. Verify current status before relying on anything below.**

## Regulatory approach

Korea became the first jurisdiction after the EU to bring a comprehensive, economy-wide AI statute into force. The Framework Act on the Development of Artificial Intelligence and the Establishment of a Foundation for Trust (the AI Framework Act or AI Basic Act, Act No. 20676, promulgated 21 January 2025) and its Enforcement Decree (Presidential Decree No. 36053) both took effect on 22 January 2026. Unlike the EU's phased rollout, Korea's provisions apply simultaneously, moderated instead by enforcement posture: the Ministry of Science and ICT (MSIT) is operating a grace period of at least one year during which fact-finding investigations and administrative fines (up to KRW 30 million) are generally deferred, except in cases of serious social harm such as loss of life or human rights violations. The statute consolidates what had been more than a dozen competing bills into a single framework that is deliberately dual-purpose: industrial promotion (R&D support, data centers, SME and startup programs, talent) alongside baseline obligations for trust, safety, transparency and user protection. MSIT describes the philosophy as minimum regulation; the correct board reading is that the obligations are real, the fines are deferred and the deferral is conditional on good-faith adoption.

The Act applies extraterritorially to AI activities affecting Korean users or the Korean market, and it distinguishes AI development business operators (those who develop and provide AI) from AI utilization business operators (those who provide products or services incorporating AI), placing most deploying corporates in scope through the second category.

## The three regulated categories

1. **Generative AI.** Operators providing products or services using generative AI must notify users in advance that AI is being used and label AI-generated outputs. The Enforcement Decree divides labeling into human-perceptible and machine-readable formats (the latter including C2PA-style metadata embedding), and even where machine-readable marking is chosen, users must be informed at least once by text or audio that content is AI-generated. Redundant labeling is waived where content, such as deepfakes likely to be confused with reality, is already labeled under other statutes. Guidance distinguishes content that stays inside a service environment (flexible UI-level disclosure) from exportable content (clearer marking expected).
2. **High-impact AI.** Systems that may significantly affect human life, physical safety or fundamental rights, with employment, healthcare, financial services, energy and public services among the recognized domains. Obligations include advance notification to users, lifecycle risk management, explanation of AI-driven outcomes where feasible, human oversight, documentation and encouraged fundamental-rights impact assessment. Internal corporate tools are not exempt: an HR system making decisions about Korean employees falls in the employment category regardless of where it was built or hosted.
3. **High-performance (large-scale) AI.** Systems trained above a cumulative compute threshold of 10^26 FLOPs, roughly ten times the EU's GPAI presumption threshold, carry safety obligations: lifecycle risk identification, assessment and mitigation, user protection measures and reporting of implementation outcomes to MSIT. The threshold deliberately captures only frontier-scale global developers.

## Cross-cutting obligations

Operators must retain documentation of risk management, explanation protocols and user protection measures for five years. Foreign operators without a Korean presence must appoint a domestic agent if they meet any threshold: prior-year global revenue of at least KRW 1 trillion, prior-year Korean AI-service revenue of at least KRW 10 billion or one million average daily Korean users, with the designation reported to MSIT. The Decree also coordinates with the Personal Information Protection Act: faithful PIPA compliance is deemed to satisfy the Framework Act's safety and reliability requirements within the scope of personal data processing, easing double regulation while leaving algorithm risk management and output accountability duties untouched.

## Governance architecture

The Act establishes a National AI Committee chaired by the President as the policy control tower, an AI Policy Center and an AI Safety Research Institute for risk evaluation and standards. An institutional improvement task force of external experts launched in March 2026 to refine implementation during the grace period, and MSIT operates a support center for compliance questions. Boards should expect subordinate guidance to keep evolving through the grace period and assign the monitoring accordingly.

## Board priorities in Korea

1. **Use the grace period as a build period.** The obligations applied on 22 January 2026; only fines are deferred, and reputational and corrective-order exposure is live. Survey evidence at commencement showed only a small minority of AI companies had formal compliance frameworks; being governed while competitors scramble is an available advantage.
2. **Classify against the three categories.** Every system in the register should carry a determination: generative, high-impact, high-performance or none. The high-impact determination is the consequential one for most corporates, and the employment category catches globally deployed HR tools that local subsidiaries did not procure and do not control. Coordinate with headquarters accordingly.
3. **Implement labeling now.** Retrofitting user notification and content marking into a shipped product is expensive; the UX and architecture decisions should be made before the enforcement posture hardens.
4. **Check the domestic agent thresholds.** Group revenue tests catch large multinationals whose Korean AI footprint is modest. The designation and MSIT reporting are administratively simple and embarrassing to miss.
5. **Leverage PIPA maturity.** Organizations with strong PIPA programs already satisfy part of the Framework Act; the gap analysis should focus on what PIPA does not cover: risk management of the algorithm itself, output accountability, labeling and documentation retention.

## Doctrine mapping

Korea's statute is notably congruent with this handbook's doctrines. The five-year documentation retention and explanation duties are [Slow AI](../01-doctrine/slow-ai.md)'s auditable and explainable tests in statutory form. The domestic agent requirement and operator accountability structure are [Final Liability](../01-doctrine/final-liability.md): a named, reachable, answerable party. The advance notification duties, human oversight requirements and high-impact determinations before deployment are [Informed Intent](../01-doctrine/informed-intent.md): authorization and disclosure precede operation.

---

**Final Liability rests with the Human.**
