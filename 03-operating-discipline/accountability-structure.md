# Accountability Structure

**An effective AI governance structure establishes named accountability, defined decision rights and escalation paths that reach the board before incidents reach the press.**

## The design principle

Structure exists to make [Final Liability](../01-doctrine/final-liability.md) operational. Every element below is a mechanism for ensuring that a named human owns each AI system, each consequential decision and each escalation, with the authority and resources to discharge the ownership. Dedicated AI committees, charters and role maps are means; visibility and named ownership are the ends. Not every organization needs new bodies. Every organization needs the board to be able to see how AI is managed, monitored and governed, and to name who answers for it.

## Executive accountability

The emerging cross-jurisdictional benchmark is ownership and accountability across the AI lifecycle: design, development, deployment, monitoring and decommissioning. Prudential regulators have begun stating this expectation explicitly for their regulated populations, and it serves as a sound yardstick for all organizations.

At minimum, larger organizations should have a senior executive, or a small set of executives with documented boundaries between them, accountable for AI governance: establishing the framework and overseeing its operation. Common patterns are a standalone role (Chief AI Officer, Chief Data Officer) or shared accountability across the CTO, CIO and equivalent senior roles. In smaller organizations the CEO typically holds it personally. Survey evidence across markets consistently shows the CEO named most often as the accountable party in small and mid-sized organizations and a technology executive in large ones, with legal and compliance executives (Chief Legal Officer, General Counsel) and risk executives carrying it in a substantial minority. Where accountability is shared, the sharing must be documented; "shared" without documentation means orphaned.

Below the executive layer, AI and data responsibilities cascade into position descriptions and role statements. The recurring failure is blur: AI responsibility smeared across cyber security, data governance and IT functions such that everyone touches it and no one owns it. Role maps, scenario testing and workshops are the practical instruments for finding and fixing the blur before an incident finds it first.

## Decision rights and escalation

The board and management should decide, and document, how AI decisions are made:

- **Approval gates.** Which AI systems and use cases require approval, at what level, against what criteria. Risk-tier the gates: low-stakes productivity tools should not queue behind the same gate as customer-facing agents or consequential decisioning. Approval criteria should include the three [Slow AI](../01-doctrine/slow-ai.md) tests and, for agentic systems, an [Informed Intent](../01-doctrine/informed-intent.md) authorization.
- **A dedicated AI committee, or not.** A management-led AI committee brings cross-functional expertise together, builds internal capability and can accelerate decisions by centralizing them. It is not mandatory. Smaller organizations can run AI decisions through existing governance, and even large organizations should watch for the failure mode observed in practice: an AI risk council whose checks duplicate existing privacy and cyber controls, slowing everything while adding nothing. The refinement seen in mature adopters is instructive: strip the overlaps and focus the dedicated body solely on AI-specific risks.
- **Escalation.** Defined triggers that move AI issues to senior management and the board: incidents, appetite breaches, novel use cases, material vendor events. AI risks that are not reported to the board, or reach it slowly, are among the clearest red flags in this discipline.

## Board reporting

Boards run on reporting, and AI reporting should be negotiated, not received. The board should agree with management the KPIs and cadence it expects, covering where AI is used across the organization, how systems perform, where risks are emerging or increasing and whether use remains within strategy and appetite. Two quality bars:

1. **Plain language.** Reporting laden with unnecessary technical vocabulary is a barrier to challenge and functions, intentionally or not, as insulation against board scrutiny. Directors should send it back.
2. **Decision-useful trend.** Reporting organized by the stable risk taxonomy (see [A working risk taxonomy](../02-board-mandate/risk-taxonomy.md)) so the board sees movement over time rather than a rotating gallery of anecdotes.

## External expertise, used without dependence

Independent external experts give boards an outside perspective on evolving AI risk and capability, and larger boards may retain one for periodic advice, including candid comparison against peer organizations. Two cautions. First, external assurance complements rather than replaces the named internal owner; the expert advises, the owner answers. Second, over-reliance on external expertise is itself a strategic weakness as AI becomes core capability; the objective is to import judgment while building it.

## Review

Structures decay. Roles, decision processes and reporting arrangements should be reviewed periodically against changing business operations, use cases, vendors and technology, with management required to adapt the framework where gaps emerge. A named trigger list (new agentic deployment, new vendor of systemic importance, entry into a regulated use case, regulatory change in a covered jurisdiction) works better than an annual calendar entry alone.

## Board questions for this element

1. Can we name the executive accountable for AI governance, and does that person have the authority and resources the role requires?
2. Do we understand how AI is being adopted across the organization and the opportunities and risks of that use?
3. Is there an effective structure for decision-making on AI use, including high-risk uses, and should a management-led AI committee exist, or be simplified?
4. Do we receive timely, comprehensive, plain-language reporting on AI use, and is it periodically renegotiated?

---

**Final Liability rests with the Human.**
