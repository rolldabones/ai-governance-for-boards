# Final Liability

**Doctrine statement: every material outcome produced by an AI system attaches to a named human owner. There is no such thing as an outcome the model is responsible for.**

## The problem Final Liability answers

AI creates a new and seductive form of accountability laundering. When a human employee makes a bad credit decision, mishandles a customer or breaches a regulation, the chain of responsibility is familiar: the employee, the supervisor, the executive, the board. When an AI system does the same thing, organizations reach instinctively for a fourth party: the model did it, the vendor trained it, the data was biased. Courts and regulators have already rejected this move. In the widely cited Canadian case involving an airline's website chatbot, the tribunal dismissed the argument that the company was not responsible for its own chatbot's misstatements. Vietnam's AI Law writes the principle into statute: AI assists humans and humans retain oversight of important decisions. Australian regulators have stated plainly that directors' duties extend to the use of AI. The direction of travel is uniform across jurisdictions: the organization, and through it named humans, answers for the machine.

Final Liability accepts this reality in advance rather than discovering it in litigation. Before any AI system touches a material outcome, the organization names the human who owns that outcome. Not a committee, not a function, not a role description shared across three executives. A name.

## The ownership chain

Final Liability is implemented as a chain with no gaps:

1. **System owner.** A named executive accountable for a specific AI system across its lifecycle: approval, operation, monitoring, change and decommissioning. Regulatory frameworks are converging on exactly this expectation; prudential guidance in several jurisdictions now describes accountability across the AI lifecycle from design through decommissioning as the baseline.
2. **Decision owner.** For each consequential decision the system informs or makes, a named human who answers for the decision itself. Where the system operates autonomously, the decision owner is the human who authorized that autonomy, which is where this doctrine meets [Informed Intent](informed-intent.md).
3. **Board accountability.** The board owns the framework: the appetite within which owners operate, the assurance that ownership is real and the consequence when it fails. Board-level oversight of AI risk is already part of directors' existing duties in every jurisdiction in this handbook; no new statute was needed to create it.

## The test

Take any output the organization's AI produced last week that mattered: a declined applicant, a price offered, a document filed, an agent's action in a live system. Ask who owns it. If the answer takes longer than one organizational chart lookup, or if the answer is a committee, the chain is broken. Regulators run this test in the first meeting after an incident. The organization should run it first.

## Why "final"

Liability can be shared along the way. Vendors carry contractual liability, insurers carry transferred risk, employees carry conduct obligations. What cannot be shared is the residual: when contracts are exhausted and the vendor points at the deployer and the deployer points at the model, someone still answers to the regulator, the court and the harmed person. Final Liability names that person before the incident, because after the incident is too late to design an accountability structure and too early to survive not having one.

This is also why vendor reliance never dilutes the doctrine. Nearly every organization's AI is built on external providers: foundation models, cloud infrastructure, embedded SaaS features. The risks may originate with vendors; the accountability remains with the organization. Boards should oversee vendor due diligence, contractual protections, incident notification and testing rights precisely because none of those transfer final liability. They only manage it.

## Board-level application

- Require a named system owner and named decision owners as a condition of approval for any AI system touching consequential outcomes. Record the names in the AI register.
- Reject any board paper that attributes an outcome, risk or incident to "the AI," "the algorithm" or "the vendor" without naming the accountable human.
- Ensure position descriptions, delegations of authority and incentive structures reflect AI ownership. Accountability without authority and consequence is decoration.
- Confirm that the ownership chain survives personnel change. An AI register whose named owners left the company eighteen months ago is a broken chain with a paper trail.

---

**Final Liability rests with the Human.**
