# Forecast Evaluation

A forecast only matters if we can come back later and see whether it was any good.

CEI should treat every forecast like something that can be checked, not something that gets a free pass because it sounded intelligent when it was written.

## What gets recorded?

Every forecast should have enough information for someone to understand what was predicted and what the model knew at the time.

| Field | What it means |
| --- | --- |
| Forecast ID | Unique ID for the forecast |
| Issued | When the forecast was published |
| Information cutoff | The latest information the forecaster was allowed to use |
| Target | What trend, technique, behavior, or transition is being predicted |
| Time horizon | When the forecast is expected to become testable |
| Probability | Estimated likelihood |
| Evidence | Sources supporting the forecast |
| Assumptions | Conditions the forecast depends on |
| Alternatives | Other explanations or scenarios |
| Indicators | Signals that could support or weaken the forecast |
| Falsifier | What result would count against it |
| Outcome | What actually happened |
| Assessment | Correct, partially correct, incorrect, or unresolved |

The **information cutoff** is especially important. Without it, hindsight can sneak into the evaluation and make a model look much better than it really was.

---

# What should we measure?

## Calibration

If a system gives something a probability of 80%, we should eventually be able to check whether events assigned roughly that probability actually happen around 80% of the time across an appropriate set of forecasts.

Confidence should be earned from performance, not just printed beside an answer.

## Lead time

How early did the forecast identify the signal compared with when the event or trend actually became observable?

A prediction made one day before something happens and a prediction made one year before it happens aren't equally useful.

## Precision

How often did the system flag something that actually turned into a meaningful outcome?

## Recall

How many meaningful emerging trends did the system identify?

## False-positive cost

A false alarm isn't free.

If a forecast causes defenders to spend time, money, or attention on something that never materializes, that should be part of the evaluation.

## Defensive value

The most interesting question is whether a forecast can actually improve defense.

That could mean:

- Earlier detection
- Better monitoring
- Better hardening
- Faster mitigation
- Better preparedness exercises
- Better allocation of defensive resources

A prediction can be statistically interesting and still not be useful to a defender.

---

# Evaluation rules

1. Preserve the information cutoff for every forecast.
2. Do not use future information to judge what the model could have known at the time.
3. Compare complex systems against simple baselines.
4. Keep failed forecasts in the record.
5. Keep unresolved forecasts until their evaluation window closes.
6. Record changes to forecasts instead of silently overwriting history.
7. Separate retrospective analysis from genuine forward-looking prediction.

---

# Baselines matter

A complicated model doesn't automatically deserve to win.

CEI should compare forecasting systems against simple approaches such as:

- Persistence
- Historical frequency
- Simple trend extrapolation
- Domain-specific rules

If a giant AI system can't beat a much simpler baseline, that's an important result.

---

# What counts as a good forecast?

A good forecast should be:

**Specific enough to test.**

**Clear about uncertainty.**

**Based on evidence that was actually available.**

**Accompanied by a time horizon.**

**Able to fail.**

That last one matters.

A statement that can never be proven wrong isn't a useful forecast.

---

# The forecast ledger

Long term, CEI should maintain a public or reproducible forecast ledger where predictions remain visible after they are made.

That gives us a historical record of what the system believed, why it believed it, and what happened afterward.

The goal isn't to make the model look impressive.

The goal is to find out whether it actually works.