# CP-0003 — Mission Contract Freeze

Date: 2026-08-12
Status: **FROZEN**
Pilot: `MCF-PILOT-001-CIAME`

## 1. Objetivo do checkpoint

Registrar o congelamento do Mission Contract v0.1 do Pilot 001 sem autorizar `MISSION START`.

Documento canônico:

`docs/MISSION-CONTRACT-PILOT-001-v0.1.md`

Commit de criação do contrato congelado:

`ab40cf0c6998c02ac73989ca8c7c2f8f113e1ca5`

O draft anterior foi removido após o freeze; seu histórico permanece preservado pelo Git.

## 2. Decisão

`ELAB-001.2 — Mission Contract do Pilot 001 = CONCLUÍDO`

O contrato está estável o suficiente para servir como especificação normativa da missão.

**Importante:** `FROZEN` não significa `AUTHORIZED`.

Estado:

- Mission Contract: FROZEN;
- MISSION START: PROIBIDO;
- ENVELOPE A: LOCKED;
- ENVELOPE B: LOCKED;
- ENVELOPE C: LOCKED;
- ENVELOPE D: LOCKED.

## 3. Melhorias incorporadas antes do freeze

### 3.1 Baseline reprodutível

O piloto deverá registrar versão exata do MCF, configuração, agentes, modelos/ferramentas relevantes, permissões, commits normativos e demais parâmetros necessários para evitar avaliação de um moving target.

### 3.2 Runtime Mutation

Mudança material no framework depois do início deverá ser registrada e pode exigir pausa, gate, segmentação, restart ou redução da confiança de medição.

### 3.3 Entity Collision Rule

A missão agora exige resolução explícita da identidade da CIAME de São Lourenço da Mata/PE antes de combinar fontes. Isso reduz risco de misturar clínicas ou empresas homônimas.

### 3.4 Temporal validity

Informação histórica, atual, possivelmente desatualizada e sem data confiável deve permanecer separada.

### 3.5 Blindness model

Foi formalizada a diferença entre:

- `Target-Intelligence Blind` — o MCF não recebe respostas sobre a CIAME;
- `Evaluation Open-Book` — o framework sabe que está sendo avaliado e os critérios metodológicos são públicos.

Isso resolve a inconsistência decorrente de o Evaluation Lab ser um repositório público.

### 3.6 Context Fingerprint

O bootstrap efetivamente entregue ao MESTRE deverá ser preservado para futura análise de Context Sufficiency.

### 3.7 Authorization Envelopes

O escopo foi dividido em envelopes progressivos:

- A — Public Research & Internal Build;
- B — Remote Experience Research;
- C — Formal Commercial Contact;
- D — Physical / Private / Production.

Nenhum desbloqueio é transitivo.

### 3.8 Phase exit criteria

As fases da missão passaram a exigir artefato, estado, lacunas e decisão explícita de avanço.

### 3.9 Self-Assessment Freeze

A autoavaliação do MCF deverá ser congelada antes de a pontuação externa final ser revelada.

### 3.10 Pre-registration

O MESTRE deverá definir métricas internas e telemetria em P0 antes da investigação material, evitando redefinição retrospectiva de sucesso.

### 3.11 Artifact Provenance

Artefatos materiais devem possuir proveniência, versão, fase, status, entradas, responsável e identificador versionado quando aplicável.

### 3.12 Transport Integrity Rule

Mensagens retransmitidas entre MESTRE e Evaluation Lab devem ser integrais. Cortes, resumos ou alterações precisam ser registrados e podem afetar Measurement Confidence.

### 3.13 Case repository privacy

O repositório operacional do Case CIAME deverá permanecer privado/restrito no período pré-contato, salvo HUMAN_GATE específico para publicação.

### 3.14 Suspension / Abort / Invalidated

O contrato passou a distinguir falha do produto de invalidação experimental e definiu condições mínimas para suspensão, aborto e invalidação.

### 3.15 No chain-of-thought requirement

A auditoria exige decisões, justificativas resumidas e evidências, não exposição de cadeia de pensamento privada de modelos.

## 4. Dependências que continuam abertas

O Mission Contract congelado não elimina as seguintes dependências de `MISSION START`:

- MCF READY;
- Execution Baseline;
- Context Fingerprint;
- matriz HUMAN_GATE / LEANDRO_PROXY;
- Interaction Ledger;
- HUMAN_GATE Ledger;
- armazenamento privado do Evaluator Reference Dataset;
- critérios PILOT READY;
- repositório privado/restrito do Case CIAME;
- freeze protocol;
- formato mínimo do relatório final;
- autorização de LEANDRO.

O protocolo de mystery shopping é dependência apenas para desbloquear ENVELOPE B.

## 5. Próximo item

`ELAB-001.3 — congelar matriz HUMAN_GATE e poderes do LEANDRO_PROXY`.
