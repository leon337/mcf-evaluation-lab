# CP-0002 — SCORECARD FREEZE

Date: 2026-08-12
Status: **FROZEN**
Scope: `ELAB-001.1`

## Decision

LEANDRO approved the proposed external evaluation architecture with authorization for the Evaluator to apply further improvements if materially useful and then advance without another approval round.

The Evaluator identified and incorporated the following improvements before freeze:

1. separation of `MCF SYSTEM SCORE`, `CASE OUTCOME SCORE` and observational `FIELD OUTCOME`;
2. non-compensatory Critical Gates;
3. mandatory floors for governance, evidence discipline and dimensions;
4. normalized intervention and rescue rates;
5. explicit Context Sufficiency metrics;
6. Measurement Confidence A–D;
7. `NS — Not Scorable` policy to prevent denominator manipulation;
8. anti-gaming rule against rewarding volume of agents, handoffs, text, artifacts, searches, tokens or time by itself;
9. explicit freeze/change-control policy;
10. preservation of Calibration Gap as a separate self-awareness signal rather than a substitute for performance.

## Frozen normative artifact

`docs/SCORECARD-v0.1.md`

Initial scorecard freeze commit:

`cbeae48d9f1629a25d9bdba0b81262e25fb5279d`

Evaluation model alignment commit:

`1efec5fc35b8783ad9417a5d2041b85372caa928`

## Frozen verdict structure

A Pilot 001 verdict must report at least:

- MCF SYSTEM SCORE — 0–100;
- CASE OUTCOME SCORE — 0–100;
- CRITICAL_GATES — PASS/FAIL;
- Measurement Confidence — A/B/C/D;
- Context Sufficiency metrics;
- Human/Evaluator intervention metrics;
- MCF Self-Assessment;
- Calibration Gap;
- FIELD OUTCOME separately when field data exists.

## Change control

Before `MISSION START`, a material change requires a new version and checkpoint.

After `MISSION START`, a material change additionally requires explicit authorization from LEANDRO and must disclose the impact on comparability.

No silent retroactive modification of criteria is allowed.

## Result

`ELAB-001.1 — SCORECARD + PASS/FAIL CRITERIA = COMPLETE`

The next protocol item is the Mission Contract for Pilot 001.
