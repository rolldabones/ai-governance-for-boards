# Slow AI

**Doctrine statement: AI that cannot be governed, explained and audited should not be deployed, however fast it would make the business.**

## The problem Slow AI answers

Every board now faces the same pressure: competitors are adopting AI, vendors are embedding it into software the organization already licenses, and employees are using it whether or not policy permits. The default posture this pressure produces is speed. Adopt first, govern later. The failure mode is equally predictable: systems in production that no one can explain, inventory or switch off, discovered by the board only when a regulator, journalist or plaintiff finds them first.

Slow AI inverts the default. It does not mean adopting less AI or adopting it later than competitors. It means that the pace of adoption is set by the pace at which the organization can govern what it adopts. Speed is an output of governance capacity, not an input the board sets by ambition.

## The three tests

An AI system passes the Slow AI standard when the organization can answer yes to three questions, in writing, before deployment and at any time afterward:

1. **Governed.** Is there a named human owner, a documented approval, a defined scope of use and a working mechanism to suspend or withdraw the system? A system that can only be turned off by its vendor is not governed by the organization.
2. **Explainable.** Can the organization explain, to the person affected and to a regulator, what the system does, what data it uses and why a given output occurred, to the degree the use case demands? Explainability is proportionate: a document summarizer needs less than a credit decisioning model. What is never acceptable is deploying a system into a consequential decision and discovering afterward that no explanation is possible.
3. **Auditable.** Are inputs, outputs and material configuration changes logged in a form a third party could examine? If an assurance provider arrived tomorrow, would there be records to assure?

## Why boards should care

The three tests are not aspiration. They are converging into law. The EU AI Act requires logging, technical documentation, human oversight and post-market monitoring for high-risk systems. Korea's AI Framework Act requires providers to retain risk management and explanation documentation for five years. Vietnam's AI Law requires risk classification before a system is put into operation and mandates human oversight of important decisions. Australian regulators have told directors their duty of care extends to the adoption, deployment and use of AI. In the US, transparency and documentation duties are accumulating state by state. An organization built to the Slow AI standard is, by construction, most of the way to compliance in every jurisdiction covered in this handbook. An organization built for speed alone must retrofit governance under enforcement pressure, which is the most expensive way to build it.

There is also a commercial argument. Reversibility preserves optionality. An organization that can exit a vendor, roll back a model or suspend an agent negotiates from strength, adapts when the technology shifts and avoids the concentration risk of dependence on a single provider it cannot leave. Fast adopters who cannot reverse are not ahead; they are committed.

## What Slow AI is not

It is not a moratorium, a preference for legacy technology or an excuse for boards that would rather not decide. Deliberate non-adoption carries its own risk: falling behind on cost, product quality and talent is a real strategic exposure, and a board that starves the organization of AI capability has made a decision it must also own. Slow AI requires the board to fund governance capacity so that adoption can proceed. The doctrine has no patience for either recklessness or paralysis.

## In the companion works

The three tests are the board-altitude statement of the doctrine. The [GRC Workbook](https://github.com/rolldabones/grc-workbook) (Module 9) states it at enterprise altitude as calibrated release: capability deployed at the rate the organization and its affected parties can absorb without losing the capacity to govern, with release tiers, gating criteria and fallback positions an independent reviewer can inspect. The [Slow AI Kitchen](https://github.com/rolldabones/slow-ai-kitchen) states it at task altitude as the twelve-step method itself: manual first pass before AI touches the work, bounded AI use, verification before release. The formulations differ by audience; the constraint is the same. See [Companion works](../appendices/companion-works.md) for the full reconciliation.

## Board-level application

- Set adoption pace explicitly as a function of governance capacity in the AI strategy, and resource governance so capacity is not the binding constraint for long.
- Require the three tests as gating criteria in the approval process for any material AI system, and require re-testing when scope, model or vendor changes.
- Ask for the failure path in every AI proposal: how is this switched off, what replaces it and what does exit cost?
- Treat any system that fails the three tests and is already in production as an incident, not an embarrassment. Inventory it, remediate it or retire it.

---

**Final Liability rests with the Human.**
