# AI as a General-Purpose Technology

**What directors need to understand about the technology itself: enough to govern, not enough to build.**

## The categories that matter for governance

AI is not one technology, and the governance burden differs sharply by category. A board needs a working map of three categories, because risk profile, regulatory treatment and required controls follow the category.

### Traditional (analytical) AI

Systems trained to perform defined, specialized tasks: machine learning classifiers, recommendation engines, credit scoring models, facial recognition, automated decision-making. This is the category most existing regulation was written for. Its characteristic risks are bias, drift and opacity in consequential decisions, which is why automated decision-making rules (the EU AI Act's high-risk categories, Korea's high-impact AI, Colorado's automated decision-making technology regime, Australia's incoming Privacy Act disclosure duty) concentrate here.

### Generative AI

Systems that produce new content: text, images, audio, video, code. Large language models are the dominant instance. The characteristic governance issues are hallucination (coherent, confident, wrong output), IP and copyright exposure on both training inputs and generated outputs, confidentiality leakage when staff paste sensitive material into public tools and content provenance. Regulation is converging on transparency: users must be told they are dealing with AI, and synthetic content must be labeled or watermarked. Korea's generative AI labeling duty, Vietnam's watermarking requirement, the EU's Article 50 transparency obligations and California's content provenance rules are the same idea in four legal systems.

### Agentic AI

Systems that use generative AI together with tools and other systems to plan and act across multiple steps toward a goal, with configurable autonomy. This category inherits every generative AI risk and adds the risks of action: unintended or unauthorized acts, errors compounding at machine speed and continuity, coordination failures across multiple agents and an expanded attack surface spanning every system the agent touches. The control model for this category is [Informed Intent](../01-doctrine/informed-intent.md): scoped authorization, technically enforced boundaries, human checkpoints, logging and a tested exit. Boards should assume regulatory frameworks will formalize expectations here quickly; supervisory guidance in several jurisdictions already names documented agent risk appetite, agent access controls and agent action logs as baseline controls.

## Properties that change the governance problem

Four properties distinguish AI from the software boards have governed for decades:

1. **Learned, not written.** Behavior derives from patterns in training data rather than explicit rules, so behavior is harder to predict, test exhaustively and explain. Testing gives evidence, not proof.
2. **Data-dependent.** Output quality is bounded by data quality. Poor data governance surfaces as biased hiring, discriminatory profiling and flawed decisions. AI governance is therefore inseparable from data governance and from the cyber security controls that protect the data.
3. **Embedded and ambient.** AI ships inside SaaS products, productivity suites and vendor platforms, frequently without disclosure. Terminology is a tell: "model," "algorithm," "predictive analytics," "smart," "agent" and "copilot" in a vendor description all signal AI inside. Procurement and vendor review processes should treat these words as triggers for AI due diligence.
4. **Priced by usage.** Modern AI is typically priced per token, the unit in which language models consume and produce text, with output tokens usually costing more than input. Usage-based cost scales non-linearly with adoption and with the computational appetite of agentic systems, a dynamic that surprised many adopters in 2025 and 2026. Boards should require cost modeling that includes token economics, staff training and quality assurance overhead, not just license fees. See [Measuring AI value](../04-value-and-returns/measuring-ai-value.md).

## The adoption context boards are governing in

Adoption has moved decisively from pilot to production across every economy this handbook covers, propelled by cloud platforms that removed the need for specialist teams, by AI features embedded in software organizations already own and by heavy infrastructure investment. Agentic adoption is the current frontier, with surveys across 2025 and 2026 consistently showing a third or more of organizations running at least one agentic use case and a steep expected growth curve. Two implications for boards:

- **Shadow AI is the default, not the exception.** Staff use public AI tools at work whether or not policy exists. The risks are confidentiality loss on uploaded material and unverified machine output entering work products. The response is an acceptable use policy, approved-tool provisioning that gives staff a sanctioned alternative, training and monitoring, in that order. Prohibition without provisioning drives usage underground.
- **The organization's AI footprint is larger than its AI budget.** The first governance artifact is an inventory or register of AI in actual use, including embedded and shadow use, refreshed on a schedule. Everything else in this handbook operates on that inventory.

## A useful maturity ladder

Organizations use AI at four levels of ambition, and governance should be sized to the level: tactical tools (individual productivity), process transformation (redesigned end-to-end processes), systematic uplift (AI applied to core infrastructure and standard ways of working) and organizational transformation (redesigned operating model with agents working alongside employees). A board should be able to say which rung its organization's investments occupy and whether the governance framework matches that rung. Tactical-tool governance applied to an organizational-transformation ambition is the mismatch that produces headlines.

---

**Final Liability rests with the Human.**
