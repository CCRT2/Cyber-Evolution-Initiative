# Cyber Evolution

## What CEI Means By "Cyber Evolution"

CEI treats cyberspace as something that changes over time.

New technology appears. Attackers figure out how to use it. Defenders respond. Organizations change. Attackers adapt again.

So instead of looking at cybersecurity as a giant list of vulnerabilities, I want to study the changes between those events.

That means asking **how** something became common, **why** it became useful, and **what conditions made that change possible**.

---

## What can change?

### Technology

Operating systems, cloud platforms, AI systems, hardware, protocols, software architectures, and other technologies can change the attack surface.

### Attack techniques

Techniques can appear, spread, get combined with other techniques, become easier to use, or eventually stop being useful.

### Defense

Defenders change too.

Detection improves. Identity systems change. Segmentation gets deployed. Vendors ship patches. Organizations change their architecture.

Attackers react to those changes.

### Economics

Cybercrime is still a business for many actors.

Cost, access, automation, monetization, availability of tooling, and expected payoff can all affect which techniques are worth using.

### Humans and organizations

People create software. People configure systems. People make mistakes. Organizations have incentives and constraints.

Those things matter because cybersecurity isn't just a technical problem.

### Dependencies

A change in one part of the ecosystem can affect another part.

A new application architecture can change identity risk. A cloud migration can change infrastructure dependencies. A new AI capability can change how existing attack techniques are used.

CEI should study those connections instead of treating each incident as isolated.

---

# Questions Worth Testing

Some questions CEI should eventually investigate:

- What tends to happen before an attack technique becomes widespread?
- Do major new techniques usually come from completely new ideas, or combinations of older ones?
- When a defense gets better, how often do attackers move to a predictable alternative?
- Can a technology transition act as an early warning signal for a future attack pattern?
- How much does missing or biased historical data change the answer?
- Does domain knowledge improve forecasting beyond what temporal patterns alone can provide?
- Can relationships between incidents tell us more than incident counts alone?

These are research questions, not assumptions.

---

# Correlation is not enough

This is one of the most important parts of the project.

Finding that two things happened around the same time doesn't automatically tell us that one caused the other.

CEI should look for **mechanisms and transitions**.

For example, instead of only asking:

> "Did attacks using technique X increase after technology Y appeared?"

we should eventually ask:

> "What changed when technology Y appeared that could have made technique X more useful, and do similar changes appear in other parts of the ecosystem?"

The second question is harder.

It's also a lot more interesting.

---

# What would count as evidence?

A useful evolutionary finding should be supported by things we can actually point to.

That could include:

- Incident timelines
- Vulnerability data
- Malware reports
- Threat intelligence
- Technology adoption data
- Defensive changes
- Economic indicators
- Technical research
- Controlled experiments

The exact evidence needed will depend on the question being tested.

---

# What CEI should avoid

CEI should not turn hindsight into fake prediction.

Knowing today that a technique became popular in 2028 doesn't mean a model was able to know that in 2026.

Historical analysis has to preserve the information available at the time being studied.

That matters for any serious attempt at forecasting.