# Product Contract — just-one-button

## Purpose
This application exposes exactly one user-visible action.

No configuration.
No modes.
No personalization.
No stateful behavior beyond what is strictly required.

## The Button
- The button performs a single, deterministic action.
- The action is explicitly documented.
- If the action cannot be completed safely, it does nothing.

## Non-Goals
This product does NOT:
- Adapt behavior
- Learn from users
- Expose internal state
- Chain actions
- Offer multiple choices
- Pretend to be extensible

## Security Posture
- Minimal attack surface
- Server-side enforcement
- No client trust
- No silent failures

## Philosophy
Correctness > Cleverness  
Constraints > Features  
Clarity > Scale
