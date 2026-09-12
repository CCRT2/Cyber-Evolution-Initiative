# Ethics and Safety

CEI is a defensive research project.

The whole point is to make cybersecurity safer and more prepared. That means the research has to stay inside some pretty clear boundaries.

## 1. Only test what we are allowed to test

Any technical experiment must use systems, datasets, sandboxes, cyber ranges, or other environments where the researcher has explicit authorization.

No public system becomes a test target just because it would make the experiment more interesting.

## 2. Keep offensive research controlled

Some research questions may require understanding how an offensive technique works.

When that happens, reproduce only what is actually needed to answer the question, and do it in an isolated environment.

The goal is to study the behavior, not to create an excuse to attack somebody else's infrastructure.

## 3. Remember that this work is dual-use

Cybersecurity research can help defenders and still contain information that could be abused.

Before publishing something, CEI should ask:

- Does this contain unnecessary operational detail?
- Does it expose sensitive information?
- Does it create a new risk for a third party?
- Does responsible disclosure apply?

More technical detail is not automatically better research.

## 4. AI does not get the final word

A model can be wrong.

Two models can be wrong in the same direction.

A confident forecast is still a forecast.

AI-generated analysis should therefore be treated as decision support. Consequential actions should remain reviewable by a qualified human.

## 5. Keep facts separate from guesses

CEI should make it obvious which parts of a document are:

- **Observed evidence**
- **Model inference**
- **Human analysis**
- **Speculation**
- **Uncertainty**

Those categories should never get quietly blended together.

## 6. Don't rewrite history to make the model look smart

This is probably the easiest way to destroy the credibility of the entire project.

CEI should not:

- Remove failed forecasts
- Change the forecast after the fact without recording the change
- Use future information to evaluate a past prediction
- Only publish successful predictions
- Move evaluation windows around until the result looks good
- Pretend hindsight was available at the time of the forecast

If the model was wrong, the record should say that it was wrong.

## 7. Failure is part of the research

A bad prediction can still teach us something.

Maybe the evidence was weak. Maybe the model missed an important variable. Maybe the whole hypothesis was wrong.

Whatever the reason, the failure belongs in the dataset.

The standard should be simple:

> **Follow the evidence, even when the evidence tells us we were wrong.**

---

# Safety Boundary

CEI may research hypothetical adversarial behavior for defensive purposes, but active experimentation must stay inside authorized and isolated environments.

That boundary is not a footnote. It is part of the project.