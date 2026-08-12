# CP-0004 — Conversation Continuity Protocol Freeze

Date: **2026-08-12**  
Status: **FROZEN**  
Protocol: `docs/CONVERSATION-CONTINUITY-PROTOCOL-v1.1.md`

## Decision

LEANDRO approved **Protocolo de Continuidade da Conversa v1.1** and confirmed that it was added to the Project CIAME instructions.

The protocol is now also preserved in the canonical `mcf-evaluation-lab` repository to avoid dependence on chat memory and to make the LEANDRO ↔ Evaluator interaction model auditable and versioned.

## Scope

The protocol governs the conversational continuity interface between:

`LEANDRO ↔ Assistant / Evaluator`

It does **not** replace or modify:

- HUMAN_GATE;
- MCF governance;
- Mission Contract authorization;
- production/commercial/security gates;
- LEANDRO's final authority.

## Core rules frozen

- exactly three continuation options at the end of every Project CIAME response;
- explicit `SEM OPÇÕES` exception;
- one clearly recommended option;
- rationale and immediate consequence for each option;
- copy-ready response block for each option;
- project-stage section when operational state is relevant;
- canonical state must be consulted when available;
- no artificial/impossible/prohibited options;
- recommendation is not authorization;
- continuity options are not HUMAN_GATE;
- `SÓ OPÇÕES` and `SEJA BREVE` command behavior;
- state must update immediately after confirmed transitions;
- formal change control for future material revisions.

## Effect on ELAB-001

This checkpoint is a supporting governance artifact.

It does **not** complete `ELAB-001.3` and does not unlock Pilot 001.

Canonical next item remains:

`ELAB-001.3 — HUMAN_GATE / LEANDRO_PROXY`

## Mission status

`MISSION START = PROIBIDO`

No CIAME contact, mystery shopping, production action or MCF Pilot execution is authorized by this checkpoint.
