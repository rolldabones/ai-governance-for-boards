# A Working Risk Taxonomy

**Directors do not need every AI risk. They need a taxonomy stable enough to organize reporting, appetite and controls, and short enough to hold in the head.**

## Three sources of harm

Every AI harm the organization can cause traces to one of three sources. The distinction matters because the controls differ.

1. **System failure.** The AI harms because it does not perform as intended: poor or biased performance, fragility, unreliability, security vulnerability. Controls: testing and validation, monitoring for drift, human review in high-stakes contexts, security hardening.
2. **Malicious or misleading use.** The AI is deliberately used to create harm: fraud and scams, misinformation at scale, AI-powered attacks, discriminatory pricing. Controls: access management, abuse monitoring, threat modeling that includes the organization's own tools being weaponized.
3. **Inappropriate or reckless use.** The AI is used without sufficient regard for the risk of harm: surveillance without authority, deployment that hollows out critical skills, deployment at a scale whose energy and resource footprint was never considered. Controls: use-case approval gates, impact assessment, the [Informed Intent](../01-doctrine/informed-intent.md) discipline of stating purpose and scope before deployment.

The third source deserves board attention because it is the one where the organization's own enthusiasm is the threat actor.

## The eight risk areas boards should see in reporting

### 1. Cyber security

AI introduces new attack vectors and amplifies old ones. Generative AI industrializes phishing and deepfakes against the organization; the organization's own AI systems become targets through prompt manipulation and training data poisoning; agentic systems extend the attack surface to every system an agent touches. In practice these exposures are compounded most often by gaps in basic controls, above all access management and patch cadence. Supervisory guidance issued across 2026 in multiple jurisdictions carries the same two messages for boards: rapid patching and strong privileged access management, applied inside AI environments and not just around them.

### 2. Privacy and data governance

Privacy obligations attach to data flowing into AI systems and to outputs containing personal information, including inferred and incorrect information about people. Characteristic exposures: personal data used beyond its original purpose, sensitive data leaking through model outputs and customers volunteering personal information to AI agents in ways the privacy program never contemplated. Several jurisdictions now impose specific disclosure duties when automated decision-making uses personal information; see the jurisdiction guides.

### 3. Output quality and explainability

Generative systems hallucinate by construction, because they generate probabilistically. The risk is not that errors occur; it is that fluent errors pass review. Where AI informs decisions with legal or similarly significant effect, the inability to explain an outcome is itself a legal exposure in a growing set of jurisdictions. Controls: validation, staff training on limitations, mandatory human review in high-stakes contexts and documentation of model design, inputs and intended use.

### 4. Fairness and discrimination

AI inherits and amplifies bias present in training data, in unrepresentative datasets and in algorithmic design choices. Outcomes that disadvantage people on protected attributes are unlawful under existing anti-discrimination law everywhere this handbook covers, regardless of whether any AI-specific statute exists. Controls: training data representativeness assessment, bias testing across protected attributes and impact assessment before deployment into consequential decisions.

### 5. Workforce impact

AI reshapes roles, skills and headcount. Beyond industrial relations compliance (consultation duties trigger in many jurisdictions when technology materially changes work), the board should watch psychosocial risks such as job insecurity and deskilling, the trade-off between headcount reduction and workforce augmentation and the effect of transition handling on trust, retention and the ability to attract talent. Workforce impact is a board matter because it prices the organization's social license.

### 6. Shadow AI

Unapproved staff use of public AI tools, with attendant confidentiality loss and unverified output entering work products. See [AI as a general-purpose technology](ai-as-general-purpose-technology.md) for the provision-then-police response.

### 7. Vendor and supply chain concentration

Nearly all organizational AI rests on external providers, and the dependency runs deeper than the primary vendor: models are hosted on the cloud infrastructure of a small number of hyperscalers with dense commercial and shareholding relationships among them. Concentration risk, fourth-party risk and exit difficulty are structural features of the AI supply chain. Controls: due diligence proportionate to criticality, contractual rights (incident notification, testing, audit), fallback arrangements and a documented view of what exit would cost. Accountability for vendor-originated failure remains with the organization; see [Final Liability](../01-doctrine/final-liability.md).

### 8. Agentic risk

Unintended or unauthorized action, error compounding at machine speed and multi-agent coordination failure. Treated fully in [Informed Intent](../01-doctrine/informed-intent.md). Reporting flag for boards: if the risk framework does not name agentic risk distinctly, the framework predates the organization's actual exposure.

## Sustainability as an emerging reporting line

AI carries a material energy, water and hardware footprint across its lifecycle. Climate disclosure regimes are beginning to capture downstream AI emissions, in some jurisdictions as scope 3 line items covering data center and cloud usage. Boards in covered entities should confirm that AI-driven consumption is inside the reporting boundary before assurance providers ask.

## Using the taxonomy

Set appetite by risk area ([Strategy and risk appetite](../03-operating-discipline/strategy-and-risk-appetite.md)), assign controls by risk area ([Controls and assurance](../03-operating-discipline/controls-and-assurance.md)) and require management reporting in the same eight categories so the board sees trend, not anecdote. A taxonomy that changes every quarter is a dashboard; one that holds still is an instrument.

---

**Final Liability rests with the Human.**
