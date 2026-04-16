# Triage Guide

After the initial triage exchange, route based on what you learned.

## Decision Matrix

| Reversible? | Stakes | Route to |
|-------------|--------|----------|
| Yes | Low | Bias for action mode |
| Yes | High | Deep dive mode |
| No | Any | Deep dive mode |
| Unclear | Any | Ask one more clarifying question before routing |

## Reversibility Test

Reversible: can be undone within days/weeks without major cost
- Choosing a marketing channel to test
- Picking a feature to build next (can deprioritize later)
- Hiring a contractor

Irreversible: difficult or impossible to undo, or costly to reverse
- Firing someone
- Committing to a major architecture decision
- Signing a long-term contract
- Pivoting the product

## Stakes Test

Low stakes: failure is a learning, not a wound
High stakes: failure costs significant time, money, relationships, or reputation

## After Routing

Tell the user explicitly:
> "This looks like a [reversible/irreversible], [low/high]-stakes decision. I'll [bias for action / dig deeper]."

Then move to the appropriate mode in `modes.md`.
