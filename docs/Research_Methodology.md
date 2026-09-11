# Research Methodology

## Purpose

Life Mission is a long-term research program. Its core requirement is that ambitious claims must be converted into testable hypotheses.

## Research Loop

```text
Observe → Represent → Hypothesize → Forecast → Test → Measure → Compare → Update
   ↑                                                                  ↓
   └──────────────────────────── Evidence ────────────────────────────┘
```

## Evidence Hierarchy

Prefer evidence that is:

1. Reproducible.
2. Time-stamped.
3. Independently corroborated.
4. Connected to a measurable outcome.
5. Explicit about missing data and uncertainty.

## Hypothesis Format

Every significant hypothesis should define:

- **Statement:** What is expected to happen?
- **Mechanism:** Why might it happen?
- **Evidence:** What observations support it?
- **Alternatives:** What other explanations fit the evidence?
- **Prediction:** What measurable event should occur?
- **Time horizon:** When should it be observable?
- **Falsifier:** What result would count against it?
- **Confidence:** How certain is the forecast?

## Baselines First

Complex AI systems must be compared against simpler approaches. A sophisticated model is not useful merely because it produces more elaborate explanations.

At minimum, experiments should consider an appropriate baseline such as persistence, frequency-based prediction, time-series extrapolation, or a domain-specific heuristic.

## Holdout and Temporal Evaluation

Cybersecurity forecasting is especially vulnerable to leakage from the future. Whenever possible, experiments should preserve chronological order and evaluate forecasts on information that was not available at training time.

## Forecast Calibration

A forecast with 80% confidence should be correct approximately 80% of the time over a sufficiently large and appropriate evaluation set. Calibration should therefore be measured, not assumed.

## Failure Recording

Failed predictions are first-class research results. The repository should preserve them, explain plausible causes, and use them to improve future hypotheses and models.

## Safety Constraint

Any technical validation involving active security behavior must occur only in systems and environments that the researcher is explicitly authorized to test. Public or third-party infrastructure should not be used as an experiment target.
