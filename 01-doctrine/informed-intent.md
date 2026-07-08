# Informed Intent

**Doctrine statement: no AI system, and above all no AI agent, acts on the organization's behalf without prior authorization that specifies what it may do, on whose authority, within what boundaries and with what exit.**

## The problem Informed Intent answers

The governance frameworks of the last decade were built for AI that predicts and recommends. The systems now being deployed act. Agentic AI plans across multiple steps, invokes tools, moves money, sends communications, modifies records and orchestrates other systems, with varying and configurable degrees of human involvement. The defining risk of this class of system is well documented: the agent does something the organization never intended or authorized, because the instruction was ambiguous, the goal was misinterpreted or the agent erred while executing. Two properties amplify the risk. Agents operate at scale and continuously, so errors compound before anyone notices. And agents orchestrating across multiple systems expand the attack surface, because a compromised agent can reach everything the agent can reach.

The traditional control for a human employee with this kind of reach is a delegation of authority: a written instrument specifying what the person may commit the organization to, up to what value, in what domain, subject to what escalation. Informed Intent applies the same discipline to machines. It is a pre-deployment authorization, made by the human who will own the outcomes under [Final Liability](final-liability.md), that states the intent the system serves and the boundaries within which it serves it.

## The five elements of an Informed Intent authorization

1. **Purpose.** What business outcome the system is deployed to achieve, stated narrowly enough that "the agent pursued the goal in an unintended way" is detectable as a breach of authorization rather than a philosophical surprise.
2. **Scope of action.** What the system may read, modify and action; which tools and systems it may invoke; what transaction values, data categories and counterparties are within bounds. Access controls should enforce the scope technically, not merely describe it in policy.
3. **Authority.** The named human granting the authorization, who holds Final Liability for what the system does within scope, and who is answerable for having set the scope too wide.
4. **Human checkpoints.** Which actions proceed autonomously, which require human confirmation and which are prohibited outright. Every jurisdiction guide in this handbook converges on the same statutory expectation: meaningful human oversight with the ability to intervene. Informed Intent specifies where the intervention points are before deployment, not after the first incident.
5. **Exit.** How the system is suspended immediately, how its recent actions are identified and reversed where reversible, and what operates in its place. Logging and auditability of agent actions are the precondition; an agent whose actions cannot be reconstructed cannot be meaningfully recalled.

## Why written and why prior

An authorization that exists only as an engineering configuration is invisible to the board, unavailable to the incident response and unpersuasive to the regulator. Writing forces the owner to know what they are authorizing, which is the "informed" in Informed Intent. Prior matters because post-hoc ratification is not governance; it is documentation of a decision the machine already made. Regulators in multiple jurisdictions now expect a documented risk appetite for what tasks agents may perform, access controls limiting what agents can touch and logs of what they did. An Informed Intent instrument satisfies all three in one document.

## Relationship to the other doctrines

Informed Intent is the transaction-level expression of the other two doctrines. [Slow AI](slow-ai.md) says nothing deploys faster than it can be governed; the Informed Intent instrument is the governance artifact that gates deployment. [Final Liability](final-liability.md) says a named human owns every outcome; the Informed Intent instrument records which human accepted ownership and on what terms. Together the three doctrines answer the questions every AI incident inquiry asks: who allowed this, what did they allow and could they stop it?

## Board-level application

- Require an Informed Intent authorization for any agentic deployment and any AI system acting on external parties, and require renewal when scope, model or integration changes.
- Set the board-level boundary: classes of action no agent may take without human confirmation regardless of business-unit appetite, for example external payments above a threshold, regulatory filings, personnel actions and public communications.
- Ask management to demonstrate the exit, not describe it. A kill switch that has never been tested is a hypothesis.
- Include agent authorizations in the AI register so the board can see, in one document, everything currently authorized to act in the organization's name.

---

**Final Liability rests with the Human.**
