# Research Methodology

CEI is trying to answer a hard question.

That means the project needs a process that can handle being wrong.

The basic rule is simple: **turn big ideas into questions that can actually be tested.**

## The research loop

```text
Observe
   ↓
Collect Evidence
   ↓
Represent It
   ↓
Ask a Question
   ↓
Build a Hypothesis
   ↓
Make a Forecast
   ↓
Test It
   ↓
Measure the Result
   ↓
Compare Against Baselines
   ↓
Update the Hypothesis
   │
   └──────────────► back to Evidence
```

This loop matters because CEI isn't supposed to start with a conclusion and work backwards until the data agrees.

---

# Evidence

Evidence should be:

1. Traceable to a source.
2. Time-stamped when possible.
3. Reproducible when possible.
4. Supported by more than one source when the claim matters.
5. Honest about missing information and uncertainty.

The source of a claim matters just as much as the claim itself.

---

# A CEI hypothesis

A useful hypothesis should answer a few basic questions:

| Part | Question |
| --- | --- |
| Statement | What do we think might be true? |
| Mechanism | Why would it happen? |
| Evidence | What makes us think this? |
| Alternatives | What else could explain the same evidence? |
| Prediction | What should we actually observe if the hypothesis is right? |
| Time horizon | When should we be able to tell? |
| Falsifier | What would make us reject the hypothesis? |
| Confidence | How confident are we, and why? |

The goal is to make the idea specific enough that another person can challenge it.

---

# Baselines first

Before trusting a complicated AI system, compare it with something simple.

Possible baselines include:

- Historical frequency
- Persistence
- Simple trend extrapolation
- Domain-specific rules
- Other appropriate statistical models

If the complicated system doesn't beat the simple one, that's not a failure of the research.

That's the result.

---

# Don't leak the future

Cyber forecasting has a huge problem: hindsight.

A model cannot be credited for predicting something using information that only became available afterward.

Experiments should therefore preserve chronological order whenever possible and clearly define what information was available at prediction time.

This includes the training data, source publication dates, model inputs, and any human changes made during the forecasting process.

---

# Calibration

When a system says it is 80% confident, that confidence should eventually be compared with reality.

Confidence scores shouldn't just be decoration.

Calibration should be measured across enough forecasts to make the result meaningful.

---

# Record failures

CEI should keep failed predictions.

Not hide them.

Not rewrite them.

Not quietly delete them.

A failed prediction can tell us that:

- The evidence was weak.
- The mechanism was wrong.
- An important variable was missing.
- The model misunderstood the data.
- The hypothesis itself was bad.

That information can improve the next experiment.

---

# Safety

Any experiment involving active security behavior must use systems and environments where the researcher has explicit authorization to test.

Public or third-party infrastructure should not be used as an experiment target.

Simulation, sandboxing, cyber ranges, and other controlled environments should be preferred whenever they can answer the research question.

---

# What this methodology is for

This is a starting framework, not a scientific law.

As CEI runs real experiments, the methodology should change when there is evidence that it needs to change.

The process is part of the research too.