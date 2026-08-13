# Changelog

## v1.5.0 (13 August 2026)

Korea resolved from primary text. Both counsel flags removed; instrument citations corrected.

**Resolved.**

- **The high-performance AI test is conjunctive, and it has three limbs.** *[Enforcement Decree Art. 24(1).]* All three must be met: cumulative training compute of 10^26 floating-point operations or more; construction and operation applying the most advanced AI technology in current use; and a risk level giving rise to concern of wide-ranging and serious impact on human life, bodily safety and fundamental rights. Sources describing the ministerial element as an alternative trigger, or as a second limb sitting beside the FLOPs figure, are wrong on the text. Two consequences are now stated in the guide: a frontier-scale training run is necessary but not sufficient, and a sub-threshold system cannot be pulled in by ministerial action, because the compute figure is a hard floor in the Decree itself.
- **The Minister's role is measurement, not scope.** *[Art. 24(2).]* What is left to public notice by the Minister of Science and ICT is the method of calculating cumulative training compute. It is not a further gating criterion.
- **The regulated actor is the AI business operator, and that reaches deployers.** *[Act Arts. 32(1) and 2(7).]* The duty sits on the 인공지능사업자, an umbrella term covering both the development business operator, who develops and provides AI, and the utilization business operator, who provides products or services using AI provided by a development operator. The obligation is not confined to the party that performed the training run. A Korean deployer building on a third party's above-threshold model is within the addressees on the face of the statute and should not assume the duty stops with the developer. Article 32(2) requires operators to submit implementation results to the Minister.

**Currency correction.** Both instruments have been amended since the versions this guide cited. The Act in force is **Act No. 21311 of 20 January 2026**, in force 21 July 2026. The Enforcement Decree in force is **Presidential Decree No. 36506 of 20 July 2026**, in force 21 July 2026. The guide previously cited Act No. 20676 and Presidential Decree No. 36053, which are the original enactments and no longer the operative versions.

**Narrowed, still open.** ⚠ How cumulative training compute is attributed across fine-tuning and downstream modification is not answered in the Decree and falls to the calculation method to be notified under Article 24(2). Until that notice issues, an operator fine-tuning an above-threshold base model cannot determine from the text alone whether it inherits the classification. This is now a monitoring item rather than an unresolved question of law.

**Incidental fix.** The How to cite line still read v1.4.0 and was missed by the two preceding patch bumps. Corrected here.

## v1.4.1 (13 August 2026)

OJ text of the amending regulation obtained; Article 5 date corrected.

**Correction, not a currency update.** The release earlier today stated that the Article 5 application date of 2 February 2025 was "settled and not affected by the Omnibus". Having now read the Official Journal text, that is **wrong in part** and is corrected here.

- **The amending act is identified.** Regulation (EU) 2026/1744 of the European Parliament and of the Council of 8 July 2026, OJ L, 2026/1744, 24.7.2026, ELI http://data.europa.eu/eli/reg/2026/1744/oj, in force 27 July 2026. Article 1, point (40) amends the third paragraph of Article 113 of Regulation (EU) 2024/1689.
- **The pinpoint question is answered.** Article 113 is structured in unnumbered paragraphs with lettered points. The correct citation form is **"Article 113, third paragraph, point (c)"**. "Article 113(3)" is wrong and always was. The prohibition on that form, adopted this morning as a precaution, is now replaced by a positive rule.
- **Article 5 carve-out.** Amended point (a) provides that Chapters I and II apply from 2 February 2025 **with the exception of Article 5(1), first subparagraph, points (ba) and (bb), and Article 5(1a) and (1b), which apply from 2 December 2026**. The general Article 5 date stands; the prohibitions the Omnibus added are deferred. The earlier unqualified statement is struck.
- **High-risk deferrals, verbatim.** Amended point (c): Chapter III, Sections 1, 2 and 3, with the exception of Article 6(5), apply from (i) 2 December 2027 for AI systems classified as high-risk pursuant to Article 6(2) and Annex III, and (ii) 2 August 2028 for those classified pursuant to Article 6(1) and Annex I.
- **New point (d).** Articles 102 to 110 apply from 27 July 2026.
- The OJ-text gap flag is removed from every file that carried it. That outstanding item is closed.

## v1.4.0 (13 August 2026)

Boards precision pass. Four precision defects corrected and the currency and status convention adopted formally.

- **The two discharge lines recast from discharge to advance.** `06-best-practices/global-best-practices.md` said a single oversight practice "discharges obligations in all five jurisdiction guides"; `05-jurisdictions/comparison.md` said "one control, five regimes discharged". Both now say advanced, with the reason stated: no control discharges a legal obligation, because obligations are discharged only by the person on whom they fall, on the terms the instrument sets. A control reduces residual work. It does not transfer the duty and it does not end it. This aligns the handbook to the drafting rule reserving liability language for where liability genuinely lands.
- **comparison.md convergence 3 role-scoped with pinpoints.** The classification-precedes-operation convergence is real but the duty falls on different actors in each regime. Now broken out by role: EU provider classification with deployer obligations under Art. 26 and provider-assumption under Art. 25; Korea's development versus utilization operator distinction with Art. 32 separated from Arts. 33 to 35; Vietnam's provider classification with deployer reclassification duty under Decree 142/2026/ND-CP; and the US position that no state regime imposes a freestanding classification duty, the inventory being a practical precondition rather than a statutory one.
- **australia.md status line aligned to its own body text.** The status line said Australia "has confirmed it will not enact standalone AI legislation", which reads as permanent. The body says the National AI Plan of December 2025 left targeted reforms expressly open where regulatory gaps emerge. The status line now matches the body and tells the reader to treat this as a settled choice about method rather than a permanent commitment against AI-specific legislation.
- **eu.md third penalty tier added.** The guide gave the EUR 35 million / 7 percent and EUR 15 million / 3 percent tiers. The third tier, up to EUR 7.5 million or 1 percent for supplying incorrect, incomplete or misleading information to notified bodies or competent authorities, was missing. It is the tier that turns a botched regulatory response into its own offence.
- **Currency and status convention adopted.** New section in comparison.md: every changed jurisdictional claim carries a provision pinpoint, an as-at date and one of four status tags (binding law, regulator guidance, proposed, author's doctrine). Records that claims are re-dated only when re-verified, and that a status line binds only in the respects it names.

- Post-application tense pass: eu.md said Article 50 transparency duties "bite on 2 August 2026", a prospective framing for a date now past. Recast to "have applied since". Account-wide sweep found no other live instance; the Checklist tier note was checked and is durable as drafted.
- License metadata sweep folded into this release: `SPDX-License-Identifier: CC-BY-NC-SA-4.0` and the canonical Creative Commons legal code added inside the existing license file, filename unchanged, human summary retained above the legal code.

## v1.3.1 (13 August 2026)

Omnibus currency remediation. The Digital Omnibus on AI entered into force on 27 July 2026; notes describing Official Journal publication as pending are recast as operative law with dated amendment notes. The Article 5 application date of 2 February 2025 is stated as fact (Article 113, point (a)). No pinpoint to a numbered subsection of Article 113 is given: the amending regulation's Official Journal text has not been read and its renumbering is unconfirmed.

- eu.md: status line re-dated to 13 August 2026 (KST) and the Omnibus paragraph recast from publication expected to entered into force 27 July 2026, with the deferrals stated as operative law.
- appendices/references.md: the Digital Omnibus entry corrected on the same point.
- Issued same day as v1.3.0. The defect was found by the account-wide Omnibus sweep run after v1.3.0 was cut, and is corrected rather than carried.

## v1.3.0 (13 August 2026)

Boards currency pass. Jurisdiction guides re-verified against primary and official sources where retrievable; amendment notes and as-at dates added to every guide touched.

**Corrections (not currency updates).**

- **us.md: the assertion that legal services is a covered domain under Colorado SB 26-189 is STRUCK.** Verified against the statutory enumeration at C.R.S. 6-1-1701(6), which exhaustively lists education, employment, residential real estate, financial or lending services, insurance, health-care services and essential government services and public benefits. Legal services is not among them. This was an error of substance, not of currency, and the covered-domain sentence is replaced with the statutory enumeration.

**Currency updates.**

- **vietnam.md: the high-risk list is no longer pending.** Decision No. 33/2026/QD-TTg issued 30 June 2026, effective 15 August 2026. New section sets out the framing principles, determination criteria under Article 9 of the AI Law and Article 8 of Decree 142/2026/ND-CP, the six listed domains and the Decision's own transition timetable (1 September 2027 for health, education and finance; 1 March 2027 for the remainder). Risk-classification paragraph, transition timetable, board priority 2 and the doctrine mapping updated accordingly. Verification particulars and the residual annex gap recorded in the guide.
- **us.md: Colorado's ADMT regime recast from in force to enacted but enforcement-stayed**, following the stay granted 27 April 2026 in *xAI v. Weiser* (D. Colo.), which by its terms reaches legislation replacing or amending the Colorado AI Act enacted in the same session.
- **us.md: C.R.S. 6-1-1707 added** on developer and deployer fault allocation: relative fault, no joint and several liability, and indemnification for a party's own acts void as contrary to public policy under 6-1-1707(7)(a).
- **us.md: HB 26-1263 added**, verified against the Colorado General Assembly record. Signed 29 May 2026, Session Laws chapter 208, act effective 12 August 2026, operator requirements from 1 January 2027. Includes the prohibition on holding output out as provided by, endorsed by or equivalent to a licensed professional's services. Siblings HB 26-1139 and HB 26-1195 noted.

**Flagged Unknowns.**

- **korea.md: two open points added to the high-performance AI category**, both marked for counsel. Sources conflict on whether the 10^26 FLOPs threshold operates cumulatively with the criteria notified by the Minister of Science and ICT or as an alternative trigger; and the regulated actor is unresolved as between the party performing the training run, the party making the model available in Korea, or both. Primary text of the final Enforcement Decree was not obtained. The FLOPs line is not re-dated on this pass; the guide's status line now states which part was re-verified and which was not. Also records that media coverage attaching the 10^26 figure to high-impact AI is an error: Article 32 and Articles 33 to 35 are separate tracks.

**Convention introduced.** Changed jurisdictional claims now carry a provision pinpoint, an as-at date and a status tag. Applied to the content touched in this release; generalised across the guides in the next.

## v1.2.0 (15 July 2026)

Ecosystem integration release under the repository improvement program.

- Added a Part of the ecosystem section linking the canonical ECOSYSTEM.md in the profile repository plus five nearest neighbors (grc-workbook, slow-ai-kitchen, AI-Governance-Academy, the book manuscript, the-ungoverned-channel) and the Substack essays line, placed before How to cite.
- Related work consolidated: the prior section is superseded by the ecosystem section; every link it carried is preserved there. The "Where this handbook sits" section and the Companion works appendix are retained; they explain the four-repository suite rather than list links.
- Version header and How to cite updated to v1.2.0.
- No change to any Part, doctrine file, jurisdiction guide or appendix.

## v1.1.0 (July 2026)

Suite integration release. This handbook is now explicitly positioned as the board layer of the four-repository suite alongside the GRC Workbook, the Slow AI Kitchen and the AI Governance Academy.

- Added [Companion works](appendices/companion-works.md) appendix: the four-repository map, reading paths by role, the doctrine concordance reconciling the board-altitude, enterprise-altitude and task-altitude formulations of Slow AI, Informed Intent and Final Liability, a chapter-to-module concordance table and guidance on using the suite in client engagements.
- README: added "Where this handbook sits" section, Related Work, How to Cite, a fifth design principle on the single doctrine set across the suite and the full author biography aligned with the companion repositories.
- Doctrine files: added an "In the companion works" paragraph to each of the three doctrine files. The Informed Intent file now reconciles this handbook's five elements of the authorization instrument with the GRC Workbook's five conditions of a valid authorization.
- License changed from CC BY-SA 4.0 to CC BY-NC-SA 4.0, aligning with the Slow AI Kitchen and the AI Governance Academy. The GRC Workbook remains CC BY-SA 4.0 in accordance with the OCEG Red Book's share-alike terms. Content published under v1.0.0 remains available under its original license.
- No change to Parts 2 through 6, the jurisdiction guides, the glossary or the references.

## v1.0.0 (July 2026)

Initial public release.

- Doctrine layer: Slow AI, Final Liability, Informed Intent (3 files)
- Board mandate: rationale, technology categories, risk taxonomy (3 files)
- Operating discipline: strategy and appetite, accountability, controls and assurance, culture and enablers (4 files)
- Value and returns: ROI framework (1 file)
- Jurisdiction guides: cross-jurisdiction comparison table plus EU, US, Korea, Vietnam, Australia, current as at early July 2026 (6 files)
- Best practices: global practices, board questions bank, red flags, SME and NFP checklist (4 files)
- Appendices: glossary, references (2 files)

Known limitations at release: US state law landscape is in active flux (Colorado SB 26-189 obligations commence 1 January 2027; federal preemption efforts unresolved). Vietnam high-risk list and penalty decrees pending. EU Digital Omnibus adopted but Official Journal publication pending at time of writing.
