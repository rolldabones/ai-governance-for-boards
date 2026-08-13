# Jurisdiction Guide: United States

**Status: current as at 13 August 2026 (KST). The US landscape is the most unsettled in this handbook: no comprehensive federal statute, an active federal preemption push, and state laws being enacted, delayed, repealed and replaced within single legislative cycles. Verify current status before relying on anything below.**

> **Amendment note, 13 August 2026 (KST).** Three changes to the Colorado section. **First, a correction, not a currency update:** this guide previously listed legal services among SB 26-189's covered domains. It is not an enumerated covered domain and that assertion is struck. **Second**, the ADMT regime is recast from in force to enacted but enforcement-stayed, following the stay in *xAI v. Weiser*. **Third**, HB 26-1263 is added.

## Regulatory approach

The United States has no comprehensive federal AI statute. Governance operates through three layers that boards must track simultaneously:

1. **Existing federal law applied to AI.** The FTC Act's prohibition on unfair or deceptive practices (including AI-washing and deceptive AI claims), anti-discrimination law (Title VII, ECOA, FCRA, ADA) applied to algorithmic decisions, sectoral regulators (SEC, banking agencies, FDA, state insurance commissioners) and, for public companies, Delaware oversight doctrine, under which boards that fail to implement and monitor reporting systems for mission-critical risks face personal exposure. None of this waited for an AI law.
2. **Federal executive policy.** The policy direction since late 2025 has been deregulatory and preemption-oriented. A December 2025 executive order, "Ensuring a National Policy Framework for Artificial Intelligence," directed agencies to identify state AI laws that conflict with federal policy and to explore preemption levers, including litigation, agency preemption findings and conditioning certain federal funds. A national policy framework followed in March 2026 urging Congress to enact preemptive legislation, and further AI executive action followed in June 2026. As at early July 2026, no federal preemption has been enacted; the state laws below remain in force, several under active federal and constitutional challenge. Boards should treat preemption as a live uncertainty, not an accomplished fact, and prepare to the strictest applicable state standard in the interim.
3. **State statutes.** The operative binding layer for most organizations, and the most volatile.

## The state layer, as it stands

### Colorado: repealed and replaced

Colorado's SB 24-205, the first comprehensive US state AI act (high-risk systems, algorithmic discrimination duty of care, impact assessments), never took effect. After a delay from February to June 2026 and sustained industry and federal pressure, Colorado repealed it on 14 May 2026 and replaced it with SB 26-189, a narrower automated decision-making technology (ADMT) statute effective 1 January 2027. The replacement drops the risk management program, impact assessment and stand-alone algorithmic discrimination duty, and centers instead on pre-use consumer notices, explanations of adverse outcomes within 30 days, meaningful human review rights and developer documentation duties, with attorney-general-only enforcement and a cure period. Covered ADMT is technology used to make, or to be a substantial factor in making, a consequential decision in an enumerated covered domain, including for Colorado-resident employees and applicants.

*[Binding law. Pinpoint: C.R.S. 6-1-1701(6). As at 13 August 2026 (KST).]* The covered domains are exhaustively enumerated as: an education enrollment or education opportunity; employment or an employment opportunity creating or potentially creating an employer-employee relationship; the lease or purchase of residential real estate in Colorado; a financial or lending service; insurance, including underwriting, pricing, coverage and claims adjudication; health-care services; and essential government services and public benefits, including eligibility and renewal determinations.

⧉ **Legal services is not among them.** Earlier editions of this guide, and secondary commentary still circulating, list legal services as a covered domain. That is wrong on the statutory text. A law department scoping SB 26-189 obligations around its own AI tooling is scoping an obligation the statute does not impose. The point is narrow and worth stating plainly because the error is common: read the enumeration, not the summaries. Vietnam's high-risk list reaches the same result by a different route, listing only wide-scale biometric identification in public-interest civil proceedings under its litigation domain; see the [Vietnam guide](vietnam.md).

**Fault allocation between developer and deployer.** *[Binding law. Pinpoint: C.R.S. 6-1-1707. As at 13 August 2026 (KST).]* Liability is allocated on relative fault. The statute creates no joint and several liability, and at 6-1-1707(7)(a) it voids as contrary to public policy any indemnification provision between developer and deployer purporting to cover that party's own acts or omissions under Colorado anti-discrimination law. Boards negotiating AI supply contracts should note that the indemnity they are being offered may be unenforceable for the exposure they most want covered.

**Enacted but enforcement-stayed.** *[Binding law, enforcement stayed. As at 13 August 2026 (KST).]* On 9 April 2026, xAI sued Attorney General Philip J. Weiser in the District of Colorado, challenging SB 24-205 on First Amendment grounds. The Department of Justice moved to intervene in support on 24 April 2026 pursuant to Executive Order 14365, and on **27 April 2026 the court granted a joint motion staying enforcement**. As reported, the stay reaches not only the Colorado AI Act but any legislation replacing or amending it enacted during the same legislative session, which by its terms captures SB 26-189, and runs until 14 days after the court rules on the forthcoming preliminary injunction motion. Colorado's ADMT regime should therefore be read as enacted but enforcement-stayed, not as simply in force. Boards should not treat the stay as a reason to stop preparing: it is procedural, time-limited and does not bind the private plaintiffs' bar or other states.

⧉ The stay order itself was not read for this revision; the quoted scope is from secondary reporting of the docket. Obtain the docket entry before relying on the precise wording.

### Colorado: HB 26-1263, conversational AI

*[Binding law. Pinpoint: HB 26-1263, Session Laws ch. 208. As at 13 August 2026 (KST).]*

Signed 29 May 2026. The act itself took effect **12 August 2026** under the post-adjournment default for bills enacted without a safety clause; the **operator requirements apply from 1 January 2027**. Note the two dates: summaries that give only 1 January 2027 are describing the obligations, not the act.

A conversational AI service is defined as an AI system accessible to the general public that primarily simulates human conversation and interaction through adaptive textual, visual or aural communications. Operators, meaning those who develop and make such a service publicly available or offer one to a consumer, must:

- estimate the age of account holders and other users by commercially reasonable or generally accepted methods;
- where the operator knows the user is a minor, provide specified disclosures, refrain from awarding points or rewards that encourage engagement, implement technically feasible measures preventing explicit sexual conduct, intimate digital depictions and statements simulating emotional dependence, implement a protocol to stop engaging in response to prompts regarding sexual conduct with a minor, and provide privacy and account controls to the minor or a parent or guardian;
- disclose to users that the service is artificial intelligence;
- implement a protocol for prompts regarding suicidal ideation or self-harm, and report annually to the attorney general on that protocol; and
- refrain from stating that output is provided by, endorsed by or equivalent to services provided by certain licensed or certified professionals.

That last prohibition is the one to read twice. It is a labeling and holding-out restriction, not a covered-domain designation, and it is the closest Colorado comes to regulating AI that behaves like a professional. Boards deploying client-facing assistants in regulated professions should test their disclaimers against it. Two sibling bills sit alongside: HB 26-1139 on AI in health insurance coverage decisions, effective 1 January 2027, and HB 26-1195 on psychotherapy AI restrictions, effective 12 August 2026.

### Texas: TRAIGA

The Texas Responsible Artificial Intelligence Governance Act (HB 149), effective 1 January 2026, took a deliberately narrow, intent-based path. For the private sector it prohibits developing or deploying AI with the intent to incite self-harm or criminal activity, unlawfully discriminate against protected classes, infringe constitutional rights or produce child sexual abuse material and unlawful deepfakes, and it regulates state agency AI use and certain biometric and healthcare disclosure practices. Compliance with the NIST AI Risk Management Framework supports an affirmative defense. Attorney general enforcement, tiered civil penalties reaching six figures per uncurable violation plus daily penalties for continuing violations, no private right of action.

### California: volume and specificity

California regulates AI through many targeted statutes rather than one act. In force from 1 January 2026: SB 53, the Transparency in Frontier Artificial Intelligence Act, requiring developers of frontier models trained above 10^26 FLOPs to publish safety frameworks, report incidents and protect whistleblowers; and AB 2013, requiring generative AI developers to disclose training data summaries. The AI Transparency Act (SB 942), requiring generative AI providers to offer watermarks, latent disclosures and detection tools, applies from 2 August 2026, with platform provenance-detection duties phasing from 2027. CCPA automated decision-making regulations are in force with significant-decision obligations phasing from April 2027. Companion chatbot safety duties (SB 243), healthcare AI disclosure and employment ADS rules add sectoral texture. An executive order of 30 March 2026 directs development of AI safety requirements for state contractors, a procurement lever that reaches private vendors.

### The rest of the map

Illinois amended its Human Rights Act (HB 3773, effective 1 January 2026) to prohibit discriminatory employer AI use and require notice. New York City's Local Law 144 bias audits for automated employment decision tools have operated since 2023; New York State's RAISE Act, signed December 2025 and amended March 2026, imposes frontier-model safety duties from 1 January 2027. Utah's AI Policy Act requires generative AI disclosure in consumer interactions and regulated occupations, with a safe harbor for prominent upfront disclosure. Beyond these, thirty-eight-plus states regulate deepfakes, election synthetic media or nonconsensual intimate imagery, and every state introduced AI legislation in 2025. Virginia's broad AI bill was vetoed; broad bills remain pending in several states.

## Board priorities in the US

1. **Build once to the strictest standard.** The major state regimes overlap heavily on inventory, disclosure, human review and documentation. A single program anchored on the NIST AI RMF covers most of the overlap, earns an affirmative defense in Texas and positions the organization for whichever way preemption resolves. Waiting for the patchwork to settle is a strategy of maximum retrofit cost.
2. **Employment AI is the hottest surface.** Illinois, NYC, Colorado's ADMT regime (enacted, enforcement stayed) and federal anti-discrimination enforcement all converge on hiring, evaluation, monitoring and termination tools. Any AI in the HR stack belongs in the register with a named owner, bias testing and notice compliance.
3. **Mind the FTC and the plaintiffs' bar.** Deceptive AI capability claims (AI-washing), chatbot misrepresentations and dark-pattern AI interactions are enforceable today under Section 5 and state UDAP statutes, with no new law required.
4. **Frontier and transparency duties reach vendors, so contract for them.** Most deployers will meet SB 53, AB 2013 and SB 942 obligations only through their providers' compliance; procurement should be obtaining the artifacts.
5. **Track the preemption docket quarterly.** Commerce and FTC deliverables under the December 2025 executive order, DOJ litigation activity and any congressional preemption vehicle can reorder this entire section with little notice. Assign the watch to a named owner; in this handbook's terms, regulatory volatility is itself a risk with [Final Liability](../01-doctrine/final-liability.md) attached.

## Doctrine mapping

The US patchwork rewards exactly what the doctrines prescribe: an inventory and named ownership ([Final Liability](../01-doctrine/final-liability.md)) because obligations attach state by state to specific systems; documented, scoped, human-reviewable deployment ([Informed Intent](../01-doctrine/informed-intent.md)) because notices, explanations and human review rights are the common denominator of Colorado, California and Illinois; and reversibility ([Slow AI](../01-doctrine/slow-ai.md)) because in a jurisdiction this volatile, the ability to reconfigure or withdraw a system cheaply is the difference between a legal change and a crisis.

---

**Final Liability rests with the Human.**
