# MCF Evaluation Lab

Laboratório independente para avaliar, medir e auditar o desempenho do **MCF — Multiagent Collaboration Framework** em missões reais.

## Estado atual

**Versão de fundação:** v0.1  
**Status:** preparação do laboratório  
**Execução do Pilot 001:** BLOQUEADA até o MCF ser explicitamente declarado pronto por LEANDRO.

## Propósito

O MCF Evaluation Lab existe para separar a **execução do framework** da **avaliação do framework**.

O laboratório deve:

- definir critérios de avaliação antes de cada piloto;
- preservar logs, checkpoints e evidências;
- medir autonomia, coordenação, governança, qualidade e eficiência;
- registrar toda interação externa necessária para a missão;
- medir dependência de contexto inicial e intervenção humana;
- comparar a autoavaliação do MCF com uma avaliação independente;
- produzir relatórios de piloto reutilizáveis para evolução do framework.

## Separação de responsabilidades

Existem três projetos distintos:

1. **MCF** — framework propriamente dito: `leon337/multiagent-collaboration-framework`.
2. **MCF Evaluation Lab** — este repositório, responsável pelo protocolo e pela avaliação independente.
3. **Case CIAME** — projeto real separado, que terá repositório próprio e servirá como Pilot 001 do MCF quando autorizado.

## Autoridade

- **LEANDRO** é a autoridade humana final.
- O **MESTRE** é o orquestrador operacional do MCF.
- O **Evaluator** é a camada independente de avaliação.
- Um papel delegado de **LEANDRO_PROXY** poderá responder apenas gates previamente autorizados pela política de governança, sem se passar literalmente por LEANDRO.

## Pilot 001

O primeiro piloto planejado é o **CASE CIAME**, referente à CIAME — Centro Integrado de Atenção Médica, em São Lourenço da Mata/PE.

O Pilot 001 não começou. O período atual é de preparação paralela enquanto LEANDRO conclui o MCF.

## Fonte canônica

A partir do checkpoint de fundação, decisões sobre o Evaluation Lab devem ser registradas neste repositório. Memória de chat não é fonte operacional de verdade.

Consulte:

- [`docs/CHARTER.md`](docs/CHARTER.md)
- [`docs/GOVERNANCE.md`](docs/GOVERNANCE.md)
- [`docs/EVALUATION-MODEL.md`](docs/EVALUATION-MODEL.md)
- [`docs/PILOT-001-CIAME.md`](docs/PILOT-001-CIAME.md)
- [`docs/RESEARCH-ETHICS.md`](docs/RESEARCH-ETHICS.md)
- [`docs/DATA-ISOLATION.md`](docs/DATA-ISOLATION.md)
- [`docs/checkpoints/CP-0001-GENESIS.md`](docs/checkpoints/CP-0001-GENESIS.md)

## Próxima unidade de trabalho

A preparação e o congelamento do protocolo v0.1 são acompanhados pela **Issue #1 — ELAB-001**.
