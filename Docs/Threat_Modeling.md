# Threat Modeling

Threat modeling in CEI is a way to describe **what could happen, why it could happen, and what we could watch for**.

It is not supposed to be a crystal ball.

The point is to give forecasts enough technical and organizational context that we can actually test them.

## What should we model?

Cyber risk can show up at a lot of different layers:

- Hardware and firmware
- Operating systems
- Applications
- Identity and access
- Networks and communications
- Cloud and infrastructure
- Supply chains and dependencies
- People and organizations
- AI-enabled systems

The layers are connected. A change in one can create consequences somewhere else.

---

# What goes into a threat model?

For each scenario, try to record:

| Part | What to capture |
| --- | --- |
| Assets | What could be affected? |
| Trust boundaries | Where does trust change? |
| Preconditions | What has to already be true? |
| Capabilities | What would an attacker need? |
| Incentives | Why would someone do it? |
| Historical analogues | Has something similar happened before? |
| Defensive controls | What already makes it harder? |
| Indicators | What could defenders observe? |
| Uncertainty | What do we not know? |
| Consequences | What happens if the scenario occurs? |

This keeps a scenario grounded in more than just an interesting attack idea.

---

# Think about change, not just techniques

Attackers don't operate from a fixed checklist forever.

Technology changes. Defenses change. Economics change. Access to tools changes.

Those changes can make old techniques useful in new ways or create combinations that weren't practical before.

So CEI should ask things like:

> What changed?

> What did that change make possible?

> Who benefits from that capability?

> What existing defenses could push the behavior somewhere else?

That is the connection between threat modeling and cyber evolution.

---

# From a signal to a forecast

A signal by itself isn't necessarily useful.

For example, seeing more automation in an area of cybersecurity doesn't automatically mean a specific attack is coming.

The threat model gives that signal context:

```text
Signal
  ↓
What changed?
  ↓
What systems can it affect?
  ↓
Who has an incentive to use it?
  ↓
What existing defenses constrain it?
  ↓
What historical examples look similar?
  ↓
What could happen next?
```

That final step is where forecasting begins.

---

# Don't confuse scenarios with predictions

A scenario is a plausible description of something that could happen.

A forecast is a claim about what is likely enough to justify testing.

CEI should keep those separate.

You can have ten plausible scenarios and still have no reason to assign high probability to any one of them.

---

# Safety boundary

Threat models can discuss hypothetical adversarial behavior for defensive research.

Actual technical experimentation belongs in authorized, isolated environments such as labs, sandboxes, simulations, or cyber ranges.

The model should help us understand risk without turning the research process into an excuse to interact with systems we don't own or have permission to test.