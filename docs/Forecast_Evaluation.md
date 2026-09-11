# Forecast Evaluation

The mission only matters if forecasts can be tested against reality.

## Forecast Record

Each forecast should include:

| Field | Description |
|---|---|
| Forecast ID | Stable identifier |
| Issued | Date and time forecast was made |
| Target | Trend, technique, behavior, or transition being forecast |
| Horizon | Expected time window |
| Probability | Estimated likelihood |
| Evidence | Sources supporting the forecast |
| Assumptions | Conditions required for the forecast |
| Alternatives | Competing explanations or scenarios |
| Indicators | Observable signals to monitor |
| Falsifier | Result that would count against the forecast |
| Outcome | What happened afterward |
| Assessment | Correct, partially correct, incorrect, or unresolved |

## Core Metrics

### Calibration

Measure whether stated probabilities match observed frequencies.

### Lead Time

Measure how far in advance a useful signal was identified relative to later observed adoption or impact.

### Precision

Measure how often flagged future trends correspond to meaningful outcomes.

### Recall

Measure how many meaningful emerging trends were identified.

### False-Positive Cost

Not every incorrect forecast has the same consequence. Track the operational cost of unnecessary defensive work.

### Defensive Value

A forecast is especially valuable when acting on it measurably improves preparedness, detection, resilience, or time-to-mitigation.

## Evaluation Rules

1. Preserve the information cutoff used to make each forecast.
2. Never evaluate a forecast using information that was available only after the forecast date without explicitly labeling the analysis as retrospective.
3. Compare against simple baselines.
4. Record uncertainty rather than forcing binary certainty.
5. Keep incorrect forecasts in the dataset.
6. Revisit unresolved forecasts when the relevant horizon expires.

## Why This Matters

A model that tells compelling stories about possible futures may still have no predictive value. The forecast ledger exists to separate persuasive explanations from demonstrated forecasting performance.
