# AI Architecture

## The idea

CEI is not supposed to be one giant AI model that magically predicts cyber attacks.

The idea is a system made of different pieces. Each piece has a job, and the output from one part becomes evidence for the next part.

The architecture will probably change a lot as the research gets better. That's expected.

## The basic pipeline

```text
Cybersecurity Data
       │
       ▼
Collection + Sources
       │
       ▼
Normalize + Link
       │
       ▼
Cyber Knowledge Base
       │
       ▼
Study How Things Change
       │
       ▼
Generate Forecasts
       │
       ▼
Challenge The Forecasts
       │
       ▼
Create Scenarios
       │
       ▼
Test Them
       │
       ▼
Measure What Happened
       │
       └──────────────► Back Into The System
```

The important part is the loop. CEI should get better from being wrong instead of pretending the model was right all along.

---

## 1. Collect the data

CEI needs historical and current cybersecurity information before it can even try to model anything.

That can include:

- Public incident reports
- Vulnerability records
- Malware research
- Threat intelligence
- Security advisories
- Technical papers
- Defensive research
- Public legal and regulatory information
- Results from controlled experiments

Every source should keep its provenance. We need to know where a claim came from and when that information was available.

---

## 2. Clean it up and connect it

Cybersecurity data is messy as hell.

The same vulnerability, company, technique, or campaign can be described in completely different ways by different sources.

CEI needs a normalization layer that can turn those different descriptions into consistent entities, dates, relationships, and source records.

This is also where uncertainty should be stored instead of silently turning guesses into facts.

---

## 3. Build the cyber knowledge base

The long-term goal is a connected representation of cyberspace rather than a pile of isolated documents.

Things that could be connected include:

- Incidents
- Vulnerabilities
- Malware
- Attack techniques
- Threat actors or actor groups
- Campaigns
- Software and hardware
- Organizations
- Defensive technologies
- Laws and regulations
- Timelines
- Dependencies
- Observed outcomes

A graph is one possible way to represent this because relationships matter as much as the individual records.

---

## 4. Study evolution

Once the data is connected, CEI can start looking at how things change over time.

Examples of things worth studying:

- A technique becoming common
- A technique being combined with another technique
- A new technology creating a new attack surface
- Attackers changing behavior after a defensive improvement
- A capability becoming cheap or widely available
- One technique replacing another

The goal isn't to find random correlations and call them a prediction.

The goal is to understand the conditions around a transition and see whether those conditions show up again.

---

## 5. Use more than one forecasting approach

I don't want CEI to depend on one model and then discover five years later that the model was confidently full of shit.

Different approaches should be compared.

Possible research directions include:

- Time-series models
- Probabilistic models
- Graph-based models
- Retrieval-based systems
- Large language models
- Agent-based systems
- Domain-specific heuristics

The exact models are a research question, not a decision that should be locked in right now.

---

## 6. Make the models argue with each other

One of the ideas behind CEI is that independent systems can challenge a forecast instead of everybody agreeing because one model said something confidently.

A challenge system could ask:

- What evidence is missing?
- What assumptions are weak?
- What other explanation fits the same data?
- What would make this forecast wrong?
- Is the model accidentally using information from the future?

Agreement isn't proof.

Disagreement isn't failure either. Sometimes disagreement is exactly where the useful research starts.

---

## 7. Turn forecasts into scenarios

A forecast should lead to something concrete.

A scenario can include:

- What might happen
- Why the model thinks it could happen
- Supporting evidence
- Confidence
- Expected time window
- Observable indicators
- What would falsify the scenario
- Potential defensive implications

This keeps the output tied to things defenders can actually examine.

---

## 8. Validate it safely

Any active technical testing needs to happen in authorized environments.

That can include:

- Cyber ranges
- Sandboxes
- Synthetic environments
- Digital twins
- Lab infrastructure
- Controlled simulations

The purpose is to test whether a forecast tells us anything useful, not to attack random systems in the name of research.

---

## 9. Give defenders something useful

The final output should not just be a giant paragraph saying "Threats may increase."

Useful outputs might include:

- Defensive priorities
- Detection hypotheses
- Hardening recommendations
- Monitoring ideas
- Preparedness exercises
- Indicators worth watching

Humans should remain responsible for consequential decisions.

---

## 10. Keep the prediction history

Every forecast should be stored.

Not just the successful ones.

The system needs to know:

- What it predicted
- What evidence it had at the time
- What confidence it assigned
- What happened later
- Where it was wrong
- Where it was right

That history is what lets CEI measure whether the whole idea is actually working.

---

# Multi-AI research

Using two systems isn't automatically better than using one.

The useful part is independence.

Two models trained on basically the same information, using the same assumptions, can easily make the same mistake.

CEI should eventually study whether diversity in models, data, assumptions, and methods produces better forecasts than simple agreement between similar systems.

---

# Current status

This is a proposed architecture, not a finished production system.

The architecture should change when experiments show that a different approach works better.

That is part of the research.