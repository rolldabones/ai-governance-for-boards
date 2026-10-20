# AI Governance for Boards: Handbook

**Son-U Michael Paik**
CEO, GRC Solutions Korea
[www.grcskorea.com](http://www.grcskorea.com)

Version 1.7.2 | 20 October 2026 | License: CC BY-NC-SA 4.0

*This masthead gives the repository version in which this file last changed; the current repository version is in the [README](README.md).*

---

This file carries Parts 1 to 4 of the handbook in one place: the three doctrines, the board mandate, the operating discipline and the measurement of AI value. The jurisdiction guides (Part 5), the globally applicable best practices, board questions, red flags and SME and NFP checklist (Part 6) and the appendices stay as separate files, listed in the [README](README.md). The regulatory content is dated throughout, with the register of every instrument in [CURRENCY.md](CURRENCY.md); verify current status before relying on any specific provision.

## Contents

- [Part 1: Doctrine](#part-1-doctrine)
  - [Slow AI](#slow-ai)
  - [Final Liability](#final-liability)
  - [Informed Intent](#informed-intent)
- [Part 2: The Board Mandate](#part-2-the-board-mandate)
  - [Why Boards Own AI](#why-boards-own-ai)
  - [AI as a General-Purpose Technology](#ai-as-a-general-purpose-technology)
  - [A Working Risk Taxonomy](#a-working-risk-taxonomy)
- [Part 3: Operating Discipline](#part-3-operating-discipline)
  - [Strategy and Risk Appetite](#strategy-and-risk-appetite)
  - [Accountability Structure](#accountability-structure)
  - [Controls and Assurance](#controls-and-assurance)
  - [Culture and Enablers](#culture-and-enablers)
- [Part 4: Value and Returns](#part-4-value-and-returns)
  - [Measuring AI Value](#measuring-ai-value)

## Part 1: Doctrine

### Slow AI

**Doctrine statement: AI that cannot be governed, explained and audited should not be deployed, however fast it would make the business.**

*Canon: [DOCTRINE.md](https://github.com/rolldabones/rolldabones/blob/main/DOCTRINE.md#1-slow-ai), section 1. This section restates it at board altitude and adds no rule.*

#### The problem Slow AI answers

Every board now faces the same pressure: competitors are adopting AI, vendors are embedding it into software the organization already licenses, and employees are using it whether or not policy permits. The default posture this pressure produces is speed. Adopt first, govern later. The failure mode is equally predictable: systems in production that no one can explain, inventory or switch off, discovered by the board only when a regulator, journalist or plaintiff finds them first.

Slow AI inverts the default. It does not mean adopting less AI or adopting it later than competitors. It means that the pace of adoption is set by the pace at which the organization can govern what it adopts. Speed is an output of governance capacity, not an input the board sets by ambition.

#### The three tests

An AI system passes the Slow AI standard when the organization can answer yes to three questions, in writing, before deployment and at any time afterward:

1. **Governed.** Is there a named human owner, a documented approval, a defined scope of use and a working mechanism to suspend or withdraw the system? A system that can only be turned off by its vendor is not governed by the organization.
2. **Explainable.** Can the organization explain, to the person affected and to a regulator, what the system does, what data it uses and why a given output occurred, to the degree the use case demands? Explainability is proportionate: a document summarizer needs less than a credit decisioning model. What is never acceptable is deploying a system into a consequential decision and discovering afterward that no explanation is possible.
3. **Auditable.** Are inputs, outputs and material configuration changes logged in a form a third party could examine? If an assurance provider arrived tomorrow, would there be records to assure?

#### Why boards should care

The three tests are not aspiration. They are converging into law. The EU AI Act requires logging, technical documentation, human oversight and post-market monitoring for high-risk systems. Korea's AI Framework Act requires AI business operators (인공지능사업자) to retain the documents for high-impact AI measures for five years (Enforcement Decree Art. 27(2)). Vietnam's AI Law requires risk classification before a system is put into operation and mandates human oversight of important decisions. Australian regulators have told directors their duty of care extends to the adoption, deployment and use of AI. In the US, transparency and documentation duties are accumulating state by state. An organization built to the Slow AI standard is, by construction, most of the way to compliance in every jurisdiction covered in this handbook. An organization built for speed alone must retrofit governance under enforcement pressure, which is the most expensive way to build it.

There is also a commercial argument. Reversibility preserves optionality. An organization that can exit a vendor, roll back a model or suspend an agent negotiates from strength, adapts when the technology shifts and avoids the concentration risk of dependence on a single provider it cannot leave. Fast adopters who cannot reverse are not ahead; they are committed.

#### What Slow AI is not

It is not a moratorium, a preference for legacy technology or an excuse for boards that would rather not decide. Deliberate non-adoption carries its own risk: falling behind on cost, product quality and talent is a real strategic exposure, and a board that starves the organization of AI capability has made a decision it must also own. Slow AI requires the board to fund governance capacity so that adoption can proceed. The doctrine has no patience for either recklessness or paralysis.

#### Board-level application

- Set adoption pace explicitly as a function of governance capacity in the AI strategy, and resource governance so capacity is not the binding constraint for long.
- Require the three tests as gating criteria in the approval process for any material AI system, and require re-testing when scope, model or vendor changes.
- Ask for the failure path in every AI proposal: how is this switched off, what replaces it and what does exit cost?
- Treat any system that fails the three tests and is already in production as an incident, not an embarrassment. Inventory it, remediate it or retire it.

### Final Liability

**Doctrine statement: every material outcome produced by an AI system attaches to a named human owner with decision rights, oversight and the power to intervene. There is no such thing as an outcome the model is responsible for.**

*Canon: [DOCTRINE.md](https://github.com/rolldabones/rolldabones/blob/main/DOCTRINE.md#3-final-liability-rests-with-the-human), section 3. This section restates it at board altitude and adds no rule.*

#### The problem Final Liability answers

AI creates a new and seductive form of accountability laundering. When a human employee makes a bad credit decision, mishandles a customer or breaches a regulation, the chain of responsibility is familiar: the employee, the supervisor, the executive, the board. When an AI system does the same thing, organizations reach instinctively for a fourth party: the model did it, the vendor trained it, the data was biased. Courts and regulators have already rejected this move. In *Moffatt v. Air Canada*, 2024 BCCRT 149, the British Columbia Civil Resolution Tribunal dismissed the argument that the company was not responsible for its own chatbot's misstatements. Vietnam's AI Law writes the principle into statute: AI assists humans and humans retain oversight of important decisions. Australian regulators have stated plainly that directors' duties extend to the use of AI. The direction of travel is uniform across jurisdictions: the organization, and through it named humans, answers for the machine.

Final Liability accepts this reality in advance rather than discovering it in litigation. Before any AI system touches a material outcome, the organization names the human who owns that outcome. Not a committee, not a function, not a role description shared across three executives. A name.

#### The ownership chain

Final Liability is implemented as a chain with no gaps:

1. **System owner.** A named executive accountable for a specific AI system across its lifecycle: approval, operation, monitoring, change and decommissioning. Regulatory frameworks are converging on exactly this expectation; prudential guidance in several jurisdictions now describes accountability across the AI lifecycle from design through decommissioning as the baseline.
2. **Decision owner.** For each consequential decision the system informs or makes, a named human who answers for the decision itself. Where the system operates autonomously, the decision owner is the human who authorized that autonomy, which is where this doctrine meets [Informed Intent](#informed-intent).
3. **Board accountability.** The board owns the framework: the appetite within which owners operate, the assurance that ownership is real and the consequence when it fails. Board-level oversight of AI risk is already part of directors' existing duties in every jurisdiction in this handbook; no new statute was needed to create it.

#### The three attributes and the allocation lifecycle

A name alone is not accountability. The named owner holds decision rights over the outcome, oversight of the system that produces it and the power to intervene; a person named without all three is a nominee, and naming a nominee manufactures the appearance of accountability. Accountability then runs through three moments:

1. **Named at specification.** The owner is identified before the work begins, as part of the authorization. Naming after the fact selects a scapegoat; it does not allocate accountability.
2. **Attaches at confirmation.** Accountability binds when the named owner confirms the output against criteria defined in advance: confirm; refuse; amend and confirm, each with a record.
3. **Holds through reliance.** It persists for as long as the organization or a third party relies on the output, usually far longer than the project that produced it.

#### The test

Take any output the organization's AI produced last week that mattered: a declined applicant, a price offered, a document filed, an agent's action in a live system. Ask who owns it. If the answer takes longer than one organizational chart lookup, or if the answer is a committee, the chain is broken. Regulators run this test in the first meeting after an incident. The organization should run it first.

#### Why "final"

Liability can be shared along the way. Vendors carry contractual liability, insurers carry transferred risk, employees carry conduct obligations. What cannot be shared is the residual: when contracts are exhausted and the vendor points at the deployer and the deployer points at the model, someone still answers to the regulator, the court and the harmed person. Final Liability names that person before the incident, because after the incident is too late to design an accountability structure and too early to survive not having one.

This is also why vendor reliance never dilutes the doctrine. Nearly every organization's AI is built on external providers: foundation models, cloud infrastructure, embedded SaaS features. The risks may originate with vendors; the accountability remains with the organization. Boards should oversee vendor due diligence, contractual protections, incident notification and testing rights precisely because none of those transfer final liability. They only manage it.

#### Board-level application

- Require a named system owner and named decision owners as a condition of approval for any AI system touching consequential outcomes. Record the names in the AI register.
- Reject any board paper that attributes an outcome, risk or incident to "the AI," "the algorithm" or "the vendor" without naming the accountable human.
- Ensure position descriptions, delegations of authority and incentive structures reflect AI ownership. Accountability without authority and consequence is decoration.
- Confirm that the ownership chain survives personnel change. An AI register whose named owners left the company eighteen months ago is a broken chain with a paper trail.

### Informed Intent

**Doctrine statement: no AI system, and above all no AI agent, acts on the organization's behalf without prior authorization that specifies what it may do, on whose authority, within what boundaries and with what exit.**

*Canon: [DOCTRINE.md](https://github.com/rolldabones/rolldabones/blob/main/DOCTRINE.md#2-informed-intent), section 2, which records this section's five elements as an altitude restatement in force: scope of action and human checkpoints are drawn out of boundaries. This section adds no rule.*

#### The problem Informed Intent answers

The governance frameworks of the last decade were built for AI that predicts and recommends. The systems now being deployed act. Agentic AI plans across multiple steps, invokes tools, moves money, sends communications, modifies records and orchestrates other systems, with varying and configurable degrees of human involvement. The defining risk of this class of system is well documented: the agent does something the organization never intended or authorized, because the instruction was ambiguous, the goal was misinterpreted or the agent erred while executing. Two properties amplify the risk. Agents operate at scale and continuously, so errors compound before anyone notices. And agents orchestrating across multiple systems expand the attack surface, because a compromised agent can reach everything the agent can reach.

The traditional control for a human employee with this kind of reach is a delegation of authority: a written instrument specifying what the person may commit the organization to, up to what value, in what domain, subject to what escalation. Informed Intent applies the same discipline to machines. It is a pre-deployment authorization, made by a human who holds, or names the human who holds, [Final Liability](#final-liability) for the outcomes, that states the intent the system serves and the boundaries within which it serves it.

#### The five elements of an Informed Intent authorization

1. **Purpose.** What business outcome the system is deployed to achieve, stated narrowly enough that "the agent pursued the goal in an unintended way" is detectable as a breach of authorization rather than a philosophical surprise.
2. **Scope of action.** What the system may read, modify and action; which tools and systems it may invoke; what transaction values, data categories and counterparties are within bounds. Access controls should enforce the scope technically, not merely describe it in policy.
3. **Authority.** The named human granting the authorization, who holds, or names the human who holds, Final Liability for what the system does within scope, and who is answerable for having set the scope too wide. The signature counts only where the authorizer has the knowledge, evidence, authority, time and permission to give it (DOCTRINE.md section 2).
4. **Human checkpoints.** Which actions proceed autonomously, which require human confirmation and which are prohibited outright. Every jurisdiction guide in this handbook converges on the same statutory expectation: meaningful human oversight with the ability to intervene. Informed Intent specifies where the intervention points are before deployment, not after the first incident.
5. **Exit.** How the system is suspended immediately, how its recent actions are identified and reversed where reversible, and what operates in its place. Logging and auditability of agent actions are the precondition; an agent whose actions cannot be reconstructed cannot be meaningfully recalled.

#### Why written and why prior

An authorization that exists only as an engineering configuration is invisible to the board, unavailable to the incident response and unpersuasive to the regulator. Writing forces the owner to know what they are authorizing, which is the "informed" in Informed Intent. Prior matters because post-hoc ratification is not governance; it is documentation of a decision the machine already made. Regulators in multiple jurisdictions now expect a documented risk appetite for what tasks agents may perform, access controls limiting what agents can touch and logs of what they did. An Informed Intent instrument satisfies all three in one document.

#### Relationship to the other doctrines

Informed Intent is the transaction-level expression of the other two doctrines. [Slow AI](#slow-ai) says nothing deploys faster than it can be governed; the Informed Intent instrument is the governance artifact that gates deployment. [Final Liability](#final-liability) says a named human owns every outcome; the Informed Intent instrument records which human accepted ownership and on what terms. Together the three doctrines answer the questions every AI incident inquiry asks: who allowed this, what did they allow and could they stop it?

#### Board-level application

- Require an Informed Intent authorization for any agentic deployment and any AI system acting on external parties, and require renewal when scope, model or integration changes.
- Set the board-level boundary: classes of action no agent may take without human confirmation regardless of business-unit appetite, for example external payments above a threshold, regulatory filings, personnel actions and public communications.
- Ask management to demonstrate the exit, not describe it. A kill switch that has never been tested is a hypothesis.
- Include agent authorizations in the AI register so the board can see, in one document, everything currently authorized to act in the organization's name.

## Part 2: The Board Mandate

### Why Boards Own AI

**The board's accountability for AI is not new law. It is the application of existing directors' duties to a technology that concentrates existing risks and adds several of its own.**

#### The legal position, globally

No major jurisdiction has created a separate regime of "AI directors' duties," and none needed to. The duty of care and diligence, the duty of good faith and the duty of oversight already extend to any technology material to the organization's operations, risk profile or strategy. Regulators have been explicit about the application to AI:

- **Australia** put it most directly. The securities regulator has stated that directors' duties of care and diligence extend to the adoption, deployment and use of AI, including awareness of AI use within the company, the extent of reliance on AI-generated information and the reasonably foreseeable risks. A 2026 Federal Court judgment on directors' use of AI in analyzing board papers cautioned, as commentary reports it, that directors should not become reliant on computer-generated output.
- **Korea** enacted a comprehensive AI Framework Act, effective 22 January 2026, whose obligations fall on the business operator, which in governance terms means the board and executives who direct it.
- **The EU** allocates AI Act obligations to providers and deployers as undertakings; sanctions scale to global group turnover, which places the exposure squarely at the level the board governs.
- **Vietnam's** AI Law, effective 1 March 2026, assigns duties to developers, providers and deployers and anchors the whole framework in human responsibility for important decisions.
- **The US** has no comprehensive federal statute, but Delaware oversight doctrine, sectoral regulators and state attorneys general reach the same result: boards that fail to implement and monitor reporting systems for a mission-critical risk are exposed, and AI is rapidly becoming mission-critical everywhere.

The practical consequence: a board waiting for an "AI law" before organizing oversight has misread the situation. In most jurisdictions the duty already attached; the AI-specific statutes only add prescription on top of it.

#### Why AI cannot be delegated into the IT portfolio

AI investments are often routed through existing IT, digital or transformation governance, and much of the machinery can stay there. Three features of AI justify heightened board attention beyond ordinary technology oversight:

1. **Probabilistic behavior.** Legacy software executes rules a developer wrote; its failures are bugs. AI systems infer outputs from patterns in data; their failures include confident, plausible and wrong outputs, bias inherited from training data and behavior that shifts as models, data or usage drift. The board cannot assume that a system tested at deployment behaves the same a year later.
2. **Pervasiveness without visibility.** AI arrives embedded in vendor products, often without disclosure, and through employees using public tools without approval. An organization can have material AI exposure with zero line items labeled "AI" in the budget. Board oversight therefore begins with inventory, not with approval workflows: what is already running, whether or not anyone approved it.
3. **Cross-cutting impact.** A single AI deployment can simultaneously implicate privacy, discrimination, consumer protection, employment, safety, IP and cyber obligations, plus the organization's workforce, its customers and its social license. No single management function sees the whole; the board is the only body positioned to demand the integrated view.

#### What board ownership actually requires

Board ownership does not mean technical expertise. Directors do not need to build models, and the mystique of the technology should never be permitted to excuse the absence of ordinary governance questions. Ownership means four things:

- **Literacy sufficient to interrogate.** Enough understanding to ask the right questions, recognize a non-answer and know when to seek independent expertise. Where the board lacks this, the options are the usual ones: training, recruitment or an advisory panel it can call on.
- **Setting the frame.** The board owns the AI risk appetite, the values that govern adoption and the strategic direction. Management owns execution within the frame. See [Strategy and risk appetite](#strategy-and-risk-appetite).
- **Assurance that the frame holds.** Reporting on where AI is used, how it performs, what risks are emerging and whether use remains within appetite, plus independent assurance proportionate to the stakes. See [Controls and assurance](#controls-and-assurance).
- **Discipline over its own use.** Boards increasingly use AI on their own papers and minutes. The same doctrines apply in the boardroom: directors do not substitute machine summaries for their own interrogation of board materials, board and committee AI use goes on the AI register and an agreed policy governs it. The court warning cited above was addressed to directors, not to management.

#### The dual risk the board balances

AI oversight is not only downside protection. Deliberate under-adoption is a governance failure with a slower fuse: organizations that fall behind on cost, product quality, customer experience and talent attraction discover the strategic cost years later, when it is expensive to close. The board's mandate is the whole opportunity-risk dynamic, which is exactly why it cannot be delegated to a risk function alone or a growth function alone. [Slow AI](#slow-ai) resolves the tension: nothing is deployed until it can be governed, explained and audited, and the board funds governance capacity so that meeting that precondition does not become the constraint on competitive adoption.

### AI as a General-Purpose Technology

**What directors need to understand about the technology itself: enough to govern, not enough to build.**

#### The categories that matter for governance

AI is not one technology, and the governance burden differs sharply by category. A board needs a working map of three categories, because risk profile, regulatory treatment and required controls follow the category.

##### Traditional (analytical) AI

Systems trained to perform defined, specialized tasks: machine learning classifiers, recommendation engines, credit scoring models, facial recognition, automated decision-making. This is the category most existing regulation was written for. Its characteristic risks are bias, drift and opacity in consequential decisions, which is why automated decision-making rules (the EU AI Act's high-risk categories, Korea's high-impact AI, Colorado's automated decision-making technology regime, Australia's incoming Privacy Act disclosure duty) concentrate here.

##### Generative AI

Systems that produce new content: text, images, audio, video, code. Large language models are the dominant instance. The characteristic governance issues are hallucination (coherent, confident, wrong output), IP and copyright exposure on both training inputs and generated outputs, confidentiality leakage when staff paste sensitive material into public tools and content provenance. Regulation is converging on transparency: users must be told they are dealing with AI, and synthetic content must be labeled or watermarked. Korea's generative AI labeling duty, Vietnam's watermarking requirement, the EU's Article 50 transparency obligations and California's content provenance rules are the same idea in four legal systems.

##### Agentic AI

Systems that use generative AI together with tools and other systems to plan and act across multiple steps toward a goal, with configurable autonomy. This category inherits every generative AI risk and adds the risks of action: unintended or unauthorized acts, errors compounding at machine speed and continuity, coordination failures across multiple agents and an expanded attack surface spanning every system the agent touches. The control model for this category is [Informed Intent](#informed-intent): the five-element authorization (purpose, scope of action, authority, human checkpoints, exit). Its scope is enforced technically and its exit tested before go-live; every agent action is logged. Boards should assume regulatory frameworks will formalize expectations here quickly; supervisory guidance in several jurisdictions already names documented agent risk appetite, agent access controls and agent action logs as baseline controls.

#### Properties that change the governance problem

Four properties distinguish AI from the software boards have governed for decades:

1. **Learned, not written.** Behavior derives from patterns in training data rather than explicit rules, so behavior is harder to predict, test exhaustively and explain. Testing gives evidence, not proof.
2. **Data-dependent.** Output quality is bounded by data quality. Poor data governance surfaces as biased hiring, discriminatory profiling and flawed decisions. AI governance is therefore inseparable from data governance and from the cyber security controls that protect the data.
3. **Embedded and ambient.** AI ships inside SaaS products, productivity suites and vendor platforms, frequently without disclosure. Terminology is a tell: "model," "algorithm," "predictive analytics," "smart," "agent" and "copilot" in a vendor description all signal AI inside. Procurement and vendor review processes should treat these words as triggers for AI due diligence.
4. **Priced by usage.** Modern AI is typically priced per token, the unit in which language models consume and produce text, with output tokens usually costing more than input. Usage-based cost scales non-linearly with adoption and with the computational appetite of agentic systems, a dynamic that surprised many adopters in 2025 and 2026. Boards should require cost modeling that includes token economics, staff training and quality assurance overhead, not just license fees. See [Measuring AI value](#measuring-ai-value).

#### The adoption context boards are governing in

Adoption has moved decisively from pilot to production across every economy this handbook covers, propelled by cloud platforms that removed the need for specialist teams, by AI features embedded in software organizations already own and by heavy infrastructure investment. Agentic adoption is the current frontier, with surveys across 2025 and 2026 consistently showing a third or more of organizations running at least one agentic use case and a steep expected growth curve. Two implications for boards:

- **Shadow AI is the default, not the exception.** Staff use public AI tools at work whether or not policy exists. The risks are confidentiality loss on uploaded material and unverified machine output entering work products. The response is an acceptable use policy, approved-tool provisioning that gives staff a sanctioned alternative, training and monitoring, in that order. Prohibition without provisioning drives usage underground.
- **The organization's AI footprint is larger than its AI budget.** The first governance artifact is an inventory or register of AI in actual use, including embedded and shadow use, refreshed on a schedule. Everything else in this handbook operates on that inventory.

#### A useful maturity ladder

Organizations use AI at four levels of ambition, and governance should be sized to the level: tactical tools (individual productivity), process transformation (redesigned end-to-end processes), systematic uplift (AI applied to core infrastructure and standard ways of working) and organizational transformation (redesigned operating model with agents working alongside employees). A board should be able to say which rung its organization's investments occupy and whether the governance framework matches that rung. Tactical-tool governance applied to an organizational-transformation ambition is the mismatch that produces headlines.

### A Working Risk Taxonomy

**Directors do not need every AI risk. They need a taxonomy stable enough to organize reporting, appetite and controls, and short enough to hold in the head.**

#### Three sources of harm

Every AI harm the organization can cause traces to one of three sources. The distinction matters because the controls differ.

1. **System failure.** The AI harms because it does not perform as intended: poor or biased performance, fragility, unreliability, security vulnerability. Controls: testing and validation, monitoring for drift, human review in high-stakes contexts, security hardening.
2. **Malicious or misleading use.** The AI is deliberately used to create harm: fraud and scams, misinformation at scale, AI-powered attacks, discriminatory pricing. Controls: access management, abuse monitoring, threat modeling that includes the organization's own tools being weaponized.
3. **Inappropriate or reckless use.** The AI is used without sufficient regard for the risk of harm: surveillance without authority, deployment that hollows out critical skills, deployment at a scale whose energy and resource footprint was never considered. Controls: use-case approval gates, impact assessment, the [Informed Intent](#informed-intent) discipline of stating purpose and scope before deployment.

The third source deserves board attention because it is the one where the organization's own enthusiasm is the threat actor.

#### The eight risk areas boards should see in reporting

##### 1. Cyber security

AI introduces new attack vectors and amplifies old ones. Generative AI industrializes phishing and deepfakes against the organization; the organization's own AI systems become targets through prompt manipulation and training data poisoning; agentic systems extend the attack surface to every system an agent touches. In practice these exposures are compounded most often by gaps in basic controls, above all access management and patch cadence. Supervisory guidance issued across 2026 in multiple jurisdictions carries the same two messages for boards: rapid patching and strong privileged access management, applied inside AI environments and not just around them.

##### 2. Privacy and data governance

Privacy obligations attach to data flowing into AI systems and to outputs containing personal information, including inferred and incorrect information about people. Characteristic exposures: personal data used beyond its original purpose, sensitive data leaking through model outputs and customers volunteering personal information to AI agents in ways the privacy program never contemplated. Several jurisdictions now impose specific disclosure duties when automated decision-making uses personal information; see the jurisdiction guides.

##### 3. Output quality and explainability

Generative systems hallucinate by construction, because they generate probabilistically. The risk is not that errors occur; it is that fluent errors pass review. Where AI informs decisions with legal or similarly significant effect, the inability to explain an outcome is itself a legal exposure in a growing set of jurisdictions. Controls: validation, staff training on limitations, mandatory human review in high-stakes contexts and documentation of model design, inputs and intended use.

##### 4. Fairness and discrimination

AI inherits and amplifies bias present in training data, in unrepresentative datasets and in algorithmic design choices. Outcomes that disadvantage people on protected attributes are unlawful under existing anti-discrimination law everywhere this handbook covers, regardless of whether any AI-specific statute exists. Controls: training data representativeness assessment, bias testing across protected attributes and impact assessment before deployment into consequential decisions.

##### 5. Workforce impact

AI reshapes roles, skills and headcount. Beyond industrial relations compliance (consultation duties trigger in many jurisdictions when technology materially changes work), the board should watch psychosocial risks such as job insecurity and deskilling, the trade-off between headcount reduction and workforce augmentation and the effect of transition handling on trust, retention and the ability to attract talent. Workforce impact is a board matter because it prices the organization's social license.

##### 6. Shadow AI

Unapproved staff use of public AI tools, with attendant confidentiality loss and unverified output entering work products. See [AI as a general-purpose technology](#ai-as-a-general-purpose-technology) for the provision-then-police response.

##### 7. Vendor and supply chain concentration

Nearly all organizational AI rests on external providers, and the dependency runs deeper than the primary vendor: models are hosted on the cloud infrastructure of a small number of hyperscalers with dense commercial and shareholding relationships among them. Concentration risk, fourth-party risk and exit difficulty are structural features of the AI supply chain. Controls: due diligence proportionate to criticality, contractual rights (incident notification, testing, audit), fallback arrangements and a documented view of what exit would cost. Accountability for vendor-originated failure remains with the organization; see [Final Liability](#final-liability).

##### 8. Agentic risk

Unintended or unauthorized action, error compounding at machine speed and multi-agent coordination failure. Treated fully in [Informed Intent](#informed-intent). Reporting flag for boards: if the risk framework does not name agentic risk distinctly, the framework predates the organization's actual exposure.

#### Sustainability as an emerging reporting line

AI carries a material energy, water and hardware footprint across its lifecycle. Climate disclosure regimes are beginning to capture downstream AI emissions, in some jurisdictions as scope 3 line items covering data center and cloud usage. Boards in covered entities should confirm that AI-driven consumption is inside the reporting boundary before assurance providers ask.

#### Using the taxonomy

Set appetite by risk area ([Strategy and risk appetite](#strategy-and-risk-appetite)), assign controls by risk area ([Controls and assurance](#controls-and-assurance)) and require management reporting in the same eight categories so the board sees trend, not anecdote. A taxonomy that changes every quarter is a dashboard; one that holds still is an instrument.

## Part 3: Operating Discipline

### Strategy and Risk Appetite

**AI adoption decisions are grounded in organizational strategy, bounded by an explicit risk appetite and resourced honestly. Anything else is responding to the market's mood.**

#### Strategic direction

AI investment decisions belong inside the organization's existing strategy, particularly its approach to digital and technology investment, and are subject to the same capital discipline as any other significant commitment. The failure pattern to guard against is adoption for its own sake: tools acquired because competitors announced something, pilots launched because a vendor demonstrated something, spend accumulating without a business case that names the improvement sought. Pursuing AI for AI's sake produces investments unmoored from strategy that can end up destroying value rather than creating it.

The board's role is to set direction and hold the filter. Direction: where AI serves the strategy, at what level of ambition (see the maturity ladder in [AI as a general-purpose technology](#ai-as-a-general-purpose-technology)) and what the organization will not use AI for regardless of return. The filter: use cases misaligned with strategy are screened out early, before material investment, which is far cheaper than discovering misalignment at scale. Pilots are legitimate instruments of informed decision-making, provided they carry defined success metrics and a decision date rather than becoming permanent residents of the innovation budget.

#### Risk appetite for AI

The board should articulate a risk appetite specific to AI and see it reflected downward into the risk management framework, internal processes and policies. A single organization-wide sentence is rarely enough; useful AI appetite statements differentiate:

- **By technology category.** Appetite for analytical AI in back-office optimization can rationally be higher than appetite for agentic AI acting on external parties.
- **By stakeholder exposure.** Staff-facing applications versus customer-facing applications versus applications touching vulnerable populations.
- **By decision consequence.** Advisory outputs a human weighs versus automated decisions with legal or similarly significant effect. Most regulatory regimes covered in this handbook draw the sharpest line exactly here.
- **By reversibility.** Higher appetite where exit is cheap and tested, lower where deployment creates dependence. This is [Slow AI](#slow-ai) expressed in appetite language: the organization accepts more risk where it retains more optionality.

Alongside appetite, the board should articulate the organization's AI values, typically reflecting commitments to fairness, transparency and accountability, because values fill the space regulation has not yet reached. Boards will repeatedly face uses that are lawful and unwise; the question "we can, but should we?" is a board question, and it should be answered by reference to values set in advance rather than improvised under commercial pressure.

#### The baseline: know what you have

Before strategy can be set, the current state must be visible. Good practice is a detailed baseline exercise before adopting or refreshing an AI strategy: an inventory of how AI, machine learning and data tools are actually used across the organization, including embedded vendor functionality and known shadow use, and which datasets and resources that use depends on. The baseline grounds investment decisions in operational reality rather than ambition and feeds the AI register described in [Controls and assurance](#controls-and-assurance). For smaller organizations with tightly limited resources, the baseline matters more, not less: it is what allows targeting the few investments that fit existing capability.

#### Data quality as strategy, not hygiene

Organizational data is the substrate of every internal AI capability. High-quality data governance determines whether AI produces insight or confidently formatted error; poor data quality surfaces as misleading analytics, flawed decisions and discriminatory profiling or hiring. The board should have a view of underlying data volume, quality and accessibility as part of the AI strategy conversation, because the honest answer frequently reorders the roadmap: the highest-return first investment is often data remediation, not models.

#### Resourcing honestly

Management should give the board a clear, business-case-supported picture of what the strategy costs: specialist talent where scale justifies it (data science, AI architecture, cloud infrastructure engineering), external providers everywhere (all organizations rely on foundation model and platform vendors to some degree), incremental licensing as AI features are switched on inside existing SaaS estates, usage-based consumption costs that scale non-linearly and the training and support employees need to convert tools into productivity. Smaller organizations will rationally buy rather than build almost everything; the strategic question for them is which existing subscriptions already contain the capability being priced separately by a new vendor.

#### Board questions for this element

1. Do we have a clear, written understanding of the organization's strategy with AI, and does every material AI investment trace to it?
2. Have we communicated to management what we see as the key AI opportunities and the risks to be managed?
3. What is our risk appetite for AI, how does it differ across use cases, technologies and stakeholder groups, and where is it written down?
4. Do we have agreed measures of AI progress and success, including return on investment?
5. What did the baseline show, and what did it change?

### Accountability Structure

**An effective AI governance structure establishes named accountability, defined decision rights and escalation paths that reach the board before incidents reach the press.**

#### The design principle

Structure exists to make [Final Liability](#final-liability) operational. Every element below is a mechanism for ensuring that a named human owns each AI system, each consequential decision and each escalation, with the authority and resources to discharge the ownership. Dedicated AI committees, charters and role maps are means; visibility and named ownership are the ends. Not every organization needs new bodies. Every organization needs the board to be able to see how AI is managed, monitored and governed, and to name who answers for it.

#### Executive accountability

The emerging cross-jurisdictional benchmark is ownership and accountability across the AI lifecycle: design, development, deployment, monitoring and decommissioning. Prudential regulators have begun stating this expectation explicitly for their regulated populations, and it serves as a sound yardstick for all organizations.

At minimum, larger organizations should have a senior executive, or a small set of executives with documented boundaries between them, accountable for AI governance: establishing the framework and overseeing its operation. Common patterns are a standalone role (Chief AI Officer, Chief Data Officer) or shared accountability across the CTO, CIO and equivalent senior roles. In smaller organizations the CEO typically holds it personally. Survey evidence across markets consistently shows the CEO named most often as the accountable party in small and mid-sized organizations and a technology executive in large ones, with legal and compliance executives (Chief Legal Officer, General Counsel) and risk executives carrying it in a substantial minority. Where accountability is shared, the sharing must be documented; "shared" without documentation means orphaned.

Below the executive layer, AI and data responsibilities cascade into position descriptions and role statements. The recurring failure is blur: AI responsibility smeared across cyber security, data governance and IT functions such that everyone touches it and no one owns it. Role maps, scenario testing and workshops are the practical instruments for finding and fixing the blur before an incident finds it first.

#### Decision rights and escalation

The board and management should decide, and document, how AI decisions are made:

- **Approval gates.** Which AI systems and use cases require approval, at what level, against what criteria. Risk-tier the gates: low-stakes productivity tools should not queue behind the same gate as customer-facing agents or consequential decisioning. Approval criteria should include the three [Slow AI](#slow-ai) tests and, for agentic systems, an [Informed Intent](#informed-intent) authorization.
- **A dedicated AI committee, or not.** A management-led AI committee brings cross-functional expertise together, builds internal capability and can accelerate decisions by centralizing them. It is not mandatory. Smaller organizations can run AI decisions through existing governance, and even large organizations should watch for the failure mode observed in practice: an AI risk council whose checks duplicate existing privacy and cyber controls, slowing everything while adding nothing. The refinement seen in mature adopters is instructive: strip the overlaps and focus the dedicated body solely on AI-specific risks.
- **Escalation.** Defined triggers that move AI issues to senior management and the board: incidents, appetite breaches, novel use cases, material vendor events. AI risks that are not reported to the board, or reach it slowly, are among the clearest red flags in this discipline.

#### Board reporting

Boards run on reporting, and AI reporting should be negotiated, not received. The board should agree with management the KPIs and cadence it expects, covering where AI is used across the organization, how systems perform, where risks are emerging or increasing and whether use remains within strategy and appetite. Two quality bars:

1. **Plain language.** Reporting laden with unnecessary technical vocabulary is a barrier to challenge and functions, intentionally or not, as insulation against board scrutiny. Directors should send it back.
2. **Decision-useful trend.** Reporting organized by the stable risk taxonomy (see [A working risk taxonomy](#a-working-risk-taxonomy)) so the board sees movement over time rather than a rotating gallery of anecdotes.

#### External expertise, used without dependence

Independent external experts give boards an outside perspective on evolving AI risk and capability, and larger boards may retain one for periodic advice, including candid comparison against peer organizations. Two cautions. First, external assurance complements rather than replaces the named internal owner; the expert advises, the owner answers. Second, over-reliance on external expertise is itself a strategic weakness as AI becomes core capability; the objective is to import judgment while building it.

#### Review

Structures decay. Roles, decision processes and reporting arrangements should be reviewed periodically against changing business operations, use cases, vendors and technology, with management required to adapt the framework where gaps emerge. A named trigger list (new agentic deployment, new vendor of systemic importance, entry into a regulated use case, regulatory change in a covered jurisdiction) works better than an annual calendar entry alone.

#### Board questions for this element

1. Can we name the executive accountable for AI governance, and does that person have the authority and resources the role requires?
2. Do we understand how AI is being adopted across the organization and the opportunities and risks of that use?
3. Is there an effective structure for decision-making on AI use, including high-risk uses, and should a management-led AI committee exist, or be simplified?
4. Do we receive timely, comprehensive, plain-language reporting on AI use, and is it periodically renegotiated?

### Controls and Assurance

**The board oversees a comprehensive process to identify AI risks, match them with controls, verify the controls work and repeat as the technology and threat environment move.**

#### Risk management inside the existing framework

For most organizations, AI risk identification and management belongs inside the existing enterprise risk management framework, aligned to the board's AI risk appetite, rather than in a parallel structure. AI adds risks and sharpens existing ones; it does not need a second risk universe. What it does need is explicit presence: an ERM framework that never mentions AI, or a risk register with no process to assess any AI-enabled application, is the baseline red flag.

Controls are then selected by factors familiar from every other risk domain: the type of AI, the use case, the nature and severity of the risk, the appetite and the operating context. Both risks and controls are reviewed on a cycle that matches the technology's pace, which currently means at least annually with event-driven triggers, not annually alone.

#### The core policy instruments

##### The AI inventory or register

The register tracks all approved AI systems and tools with key information about each: purpose, owner (the named human of [Final Liability](#final-liability)), risk classification, data dependencies, vendor, approval date and review date. It is the board's single view of AI across the organization and the artifact every jurisdiction guide in this handbook ultimately presupposes: risk classification duties in the EU and Vietnam, high-impact determinations in Korea, automated decision-making disclosures in Australia and US states all begin with knowing what is running. As AI features embed inside broader platforms, the register should capture embedded functionality, not just standalone systems, and there must be a process that keeps it current. A register is a snapshot with a refresh process; without the process it is a souvenir.

##### The AI policy

The central policy document setting the rules and processes for AI use across the organization: which systems are approved, the rules applying to them, which are prohibited and how new use cases enter the approved list. In some organizations the staff-facing rules live in a separate acceptable use policy. The policy is owned by the senior manager accountable for AI and approved at a level matching the organization's size and complexity. Public-sector AI policy templates now exist in several jurisdictions and are serviceable starting points; the customization that matters is the mapping to the organization's own register, appetite and named owners.

#### A control catalog boards should recognize

The board does not select controls, but it should recognize whether the catalog management presents is complete. A serviceable baseline, by risk area:

| Risk area | Common controls |
|---|---|
| Cyber security | Rapid patching inside AI environments; existing controls (encryption, access control, monitoring, incident response) explicitly extended to AI-specific risks; AI threat modeling, red-teaming and penetration testing |
| Privacy | Privacy impact assessments for AI systems; privacy policies and notices updated for AI-specific data practices, including automated decision-making disclosures where required; data security across the AI lifecycle |
| Output quality | Model testing, validation and fine-tuning; staff training on limitations; human review of outputs in high-stakes contexts |
| Explainability | Documentation of model design, inputs and intended use; processes for explaining AI-driven decisions to affected individuals |
| Fairness | Representativeness and quality assessment of training data; bias testing across protected attributes; AI impact assessments |
| Shadow AI | Acceptable use policy; approved-tool provisioning; staff training on risks and obligations; monitoring of AI use across networks |
| Agentic AI | Documented risk appetite for what tasks agents may perform; access controls limiting what agents can read, modify and action; logging and auditability of agent actions; tested suspension and exit ([Informed Intent](#informed-intent)) |
| Vendor | Due diligence and pre-adoption testing consistent with appetite; visibility of vendor location, ownership and fourth-party cloud dependencies; contractual incident notification, reporting and testing rights; fallback arrangements |

#### Vendors: the four-step oversight loop

Because most AI risk enters through vendors, board oversight of the vendor layer deserves its own loop: (1) understand what testing and trialing of the vendor's product occurred before adoption and whether results sit inside appetite; (2) understand the provider's location and ownership structure, its interdependencies with other infrastructure providers and the fallback available on system failure; (3) monitor the provider's data governance and security posture on an ongoing basis; (4) confirm performance and data security are reflected in contract: reporting duties, incident notification and rights to undertake testing. Information flow diagrams mapping how data moves between the organization and AI systems, with the internal and external access points and controls at each, are a compact tool supporting both this loop and board comprehension generally.

#### Assurance

The board should have confidence, not hope, that AI risks are controlled, which means assurance in the audit sense: independent verification of control effectiveness. External assurance brings objectivity and specialized expertise internal teams may lack, and increasingly cuts across cyber security and data governance simultaneously because the underlying systems are interconnected. Internal audit's AI coverage should be on the audit plan explicitly. Smaller organizations can buy assurance in targeted, cost-effective slices, for example independent testing of how sensitive datasets are used within internal AI systems, rather than full-scope engagements. The assurance principle mirrors the accountability principle: verification can be outsourced; the obligation to be verifiable cannot.

#### The cyber and data governance junction

Cyber security recurs across every survey as the AI risk boards worry about most, and rightly, because AI risk is structurally interconnected with cyber resilience and data governance. Three synergies worth the board's attention: data classification and lifecycle management underpin both least-privilege security and safe AI deployment; strong cyber controls (secure configuration, vulnerability testing, third-party risk management) apply equally to AI workflows, including AI-generated code and agentic systems; and unified data inventories, logging and monitoring enable faster detection of cyber incidents, model failures and breaches together, with coordinated response, regulatory reporting and board oversight downstream. Boards that already run mature cyber and data governance oversight should extend those mechanisms to AI explicitly rather than building a third silo.

#### Board questions for this element

1. What steps give us confidence we are meeting legal and regulatory obligations for AI and the associated data collection, storage and use?
2. Does the risk management framework adequately address AI-related risks, and does it differentiate high-risk from low-risk applications?
3. What controls govern agentic risk, and have the suspension mechanisms been tested?
4. Do our privacy, data governance, cyber and procurement policies address AI, and when were they last reviewed for it?

### Culture and Enablers

**Governance frameworks fail in organizations that lack the infrastructure, literacy and stakeholder trust to carry them. The board should have confidence in all three.**

#### Technology and infrastructure

Significant AI investment presupposes adequate digital, data and technology infrastructure: computing capacity, data storage and network capability, understood by the board at a strategic level. Two dynamics deserve specific board attention:

- **Compute demand scales non-linearly.** Management should be assessing how demand for computing capacity from AI workloads can scale rapidly and non-linearly, especially as agentic systems multiply, and what that means for capital allocation and operating expenditure. Usage-priced AI turns adoption success into a cost event; the budget conversation should anticipate the success case, not just the pilot case.
- **Data readiness gates everything.** The availability, accessibility and security of high-quality datasets determine whether AI investment returns value or amplifies noise. Boards should oversee how data storage and management practices support AI use, and treat the recurring finding "there is no data stocktake and limited understanding of internal data quality" as the enabler-layer red flag it is.

#### AI literacy and a responsible AI culture

AI literacy means organizational steps to build understanding of the technology and support its effective, responsible use. Wherever adoption is significant, the board should gain comfort that employees are supported and trained to use AI tools consistently with policy. The literacy obligation is becoming legal as well as prudential: the EU AI Act requires providers and deployers to take measures supporting AI literacy among staff dealing with AI systems, and equivalent expectations appear in guidance across the jurisdictions this handbook covers.

A responsible AI culture is the stronger claim: an organization in which employees, and volunteers in many non-profits, feel personally committed to responsible use and reinforce it among colleagues. Culture is the only control that operates where policy cannot see, which is precisely the domain of shadow AI. The board's contribution is tone from the top, and increasingly the board models the tone through its own disciplined AI use: literacy programs that include the directors themselves, board-level AI use recorded in the register and governed by agreed policy.

Two field-tested lessons from mature adopters are worth importing. First, governance artifacts must be usable by non-specialists: organizations that simplified assessment templates into plain language, shortened them and trusted trained staff to complete them saw better compliance than those that piled on questions, and the simplification did not compromise assessment quality where prior investment in literacy had been made. Second, tying access to training works: making completion of responsible AI training a prerequisite for access to AI tools converts policy into practice at scale.

#### Stakeholder engagement

Engaging stakeholders is how the organization learns about risks and harms before they mature into incidents, and the board should be comfortable management has engaged appropriately for the deployment at hand:

- **Customers and clients.** Transparency about how AI is deployed, including use of personal information, consistent with applicable privacy law. Targeted consultation is appropriate where AI touches concerned or vulnerable groups, for example a human services organization deploying AI in service delivery; for mass-market customer bases, transparency substitutes where consultation is infeasible.
- **Employees.** Widespread adoption should be accompanied by consultation, training and support. Research repeatedly finds worker engagement is the neglected element of AI programs even though employees decide whether value is realized. In many jurisdictions consultation is also a legal duty when AI materially changes work; see the jurisdiction guides on industrial relations triggers.
- **Suppliers.** Where AI systems alter the nature of the commercial relationship or use supplier data, transparency and in some cases consultation are appropriate.
- **Broader stakeholders.** Community, government and regulators are key to reputation and social license, particularly for large deployments affecting many customers and employees. Proactive engagement is cheaper than remedial engagement.

Public trust in AI is low across markets, and organizations deploy into that deficit. Transparency beyond minimum disclosure, where the organization can stand behind it, converts a compliance posture into a credibility asset; several large adopters now publish standalone reports on their AI adoption, governance and risk management for exactly this reason.

#### Workforce transition as a governance topic

The board's role in workforce impact goes beyond compliance: understanding whether management assesses impacts across workforce segments, monitors psychosocial risks such as job insecurity and deskilling and handles displacement with transition, reskilling and redeployment. These choices trade efficiency against the value of human contribution, judgment and relationships, and they shape employee trust, retention and talent attraction over time. Under the doctrines of this handbook, they are also where [Final Liability](#final-liability) meets the workforce: decisions about how AI's gains are realized are human decisions with named owners, not outcomes the technology imposed.

#### Board questions for this element

1. Do we have a strategy for understanding the impact of AI implementation on internal and external stakeholders, and have we consulted where necessary?
2. Do we have a comprehensive view of underlying data volume and quality, and how does it constrain AI effectiveness?
3. Have cyber security and data governance processes, practices and policies been updated for AI implementation?
4. Are current technology platforms and data flows fit for purpose for safe and responsible AI, including the transparency and explanation of decisions the architecture must enable?

## Part 4: Value and Returns

### Measuring AI Value

**Organizations are investing heavily in AI while evidence on returns remains mixed. The board's job is to know whether its organization's investment is generating sustainable value, and to insist on the discipline that makes the question answerable.**

#### Why the board owns ROI oversight

Board oversight of AI return on investment serves three functions:

1. **Investment discipline.** Boards should understand what value AI investments are expected to deliver, over what timeframe and how success will be measured, exactly as for any other significant capital or operating commitment. The technology's novelty is not an exemption from the business case.
2. **Organizational focus.** Requiring clear use cases, defined success metrics and structured evaluation prevents fragmented adoption that consumes resources without delivering outcomes. The absence of this discipline has a recognizable signature: many tools, no measured improvement, rising spend.
3. **Value-risk integration.** Value and risk in AI deployment are closely connected. Systems that create significant commercial, regulatory or reputational risk can erode rather than create value; benefits achieved outside appetite are liabilities on a delay. The ROI question and the risk question are the same question asked from two sides, which is one reason this handbook treats them under one governance framework.

#### The state of the evidence

Directors should hold two findings simultaneously. Studies across 2025 and 2026 report large shares of organizations seeing no tangible profitability impact from generative AI investment and high pilot failure rates, with figures as stark as 80 percent seeing no bottom-line impact and 95 percent of pilots failing circulating widely. At the same time, majorities in other surveys report real business value, with the share rising sharply among organizations classed as AI leaders, and country-level research consistently finds substantial reported efficiency improvement. The reconciliation is in the pattern: early generative AI benefits appear as individual productivity, which does not automatically translate into bottom-line impact. Greater value is realized where AI transforms processes, systems or business models, and relatively few organizations operate at that level yet. Meanwhile pressure to demonstrate returns is intensifying; a majority of business leaders report increasing pressure to show returns on AI investment. The board's posture follows from the evidence: skeptical of aggregate claims in either direction, insistent on use-case-level measurement in its own organization.

#### A structured ROI framework

The following framework scales to organizations of any size, with evaluation effort proportionate to the opportunity, cost, risk and complexity of the deployment.

##### 1. Assess ROI per use case, not per capability

General capabilities do not have measurable ROI; specific use cases do. For each use case, identify the specific business improvement sought and the metrics that will demonstrate success, before investment.

##### 2. Match the ROI lens to the implementation phase

AI initiatives typically move through three phases, each with a distinct ROI profile: experimentation (can we do this?), integration (does it work?) and scaling (can this be rolled out?). Benefits, costs and risks rise and fall in importance across the phases; judging an experiment by scaling economics kills useful learning, and judging a scaled rollout by experiment enthusiasm hides failure.

##### 3. Take a broad view of benefits

Direct efficiency gains are the easiest to count and rarely the whole story. A clearer understanding of the range of direct and indirect benefits over time (quality, cycle time, customer experience, employee experience, risk reduction) prevents both under-crediting real value and over-crediting activity.

##### 4. Test three assumptions at integration and scaling

- **Adoption.** What proportion of the target user base actively uses the capability? Licenses purchased is not a benefit metric.
- **Translation efficiency.** How well does the targeted business improvement translate into broader organizational value? Time saved that is not redeployed is a benefit that evaporated.
- **Accuracy and performance.** Does the use case perform reliably at the quality and consistency required, including the cost of the human review layer that assures it?

##### 5. Model all relevant costs

Including usage-based token costs, which scale with adoption and with agentic complexity, staff training, quality assurance processes and the integration and change management around the tool. The most common ROI error in current practice is comparing full benefits against license-only costs.

#### Reporting to the board

Value reporting belongs in the standing AI report alongside risk reporting: use cases in flight by phase, metrics against the success criteria set at approval, adoption rates, cost against model including consumption and a kill list. The kill list matters: an organization that has never retired an underperforming AI use case is not measuring, it is accumulating. Sunsetting failed pilots on evidence is the visible proof that the measurement discipline is real, and it is the ROI expression of [Slow AI](#slow-ai): reversibility applies to investments, not only to systems.

#### Board questions for this element

1. For our three largest AI investments, what specific improvement was each meant to deliver, and what do the agreed metrics currently show?
2. Which phase is each material initiative in, and what would move it to the next phase or end it?
3. What proportion of intended users actually use each deployed capability?
4. Are consumption costs, training and quality assurance inside the cost model?
5. What have we retired in the last year, and why?

How this handbook relates to the GRC Workbook, the Slow AI Kitchen and the AI Governance Academy, and how the doctrine formulations reconcile across them, is in [Companion works](appendices/companion-works.md).

---

**Final Liability rests with the Human.**
