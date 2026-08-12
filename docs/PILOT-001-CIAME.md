# Pilot 001 — CASE CIAME

Status: **PLANEJADO / EXECUÇÃO BLOQUEADA**

## 1. Identidade

O Pilot 001 será a primeira missão empresarial real utilizada para avaliar formalmente o MCF.

Alvo-semente:

**CIAME — Centro Integrado de Atenção Médica**  
São Lourenço da Mata/PE.

A identidade empresarial concreta do alvo deverá ser resolvida pela própria missão antes da consolidação do corpus factual, seguindo a `Entity Collision Rule` do Mission Contract.

O Case CIAME terá repositório próprio e separado do MCF e do Evaluation Lab.

## 2. Objetivos simultâneos

O Pilot 001 deverá produzir evidência para quatro perguntas diferentes:

1. o MCF consegue executar uma missão empresarial real com coordenação multiagente confiável?
2. o trabalho produzido para a CIAME é tecnicamente, comercialmente e operacionalmente forte?
3. quanto contexto inicial uma missão dessa classe precisa para funcionar bem?
4. a complexidade do MCF gera benefício suficiente em relação a uma execução convencional?

## 3. Avaliação oficial

O Pilot 001 será avaliado segundo o scorecard externo congelado em:

`docs/SCORECARD-v0.1.md`

Estrutura obrigatória:

- MCF SYSTEM SCORE — 0–100;
- CASE OUTCOME SCORE — 0–100;
- CRITICAL_GATES — PASS/FAIL;
- Measurement Confidence — A/B/C/D;
- Context Sufficiency metrics;
- Human/Evaluator intervention metrics;
- MCF Self-Assessment;
- Calibration Gap;
- FIELD OUTCOME separadamente, quando houver dados reais de campo.

O congelamento do scorecard está registrado em:

`docs/checkpoints/CP-0002-SCORECARD-FREEZE.md`

## 4. Mission Contract oficial

O Mission Contract v0.1 está congelado em:

`docs/MISSION-CONTRACT-PILOT-001-v0.1.md`

Checkpoint:

`docs/checkpoints/CP-0003-MISSION-CONTRACT-FREEZE.md`

O contrato congelado não autoriza execução.

`MISSION START = PROIBIDO` até satisfação das dependências e autorização formal de LEANDRO.

## 5. Princípio de missão limpa

O MCF não deverá receber como contexto inicial diagnósticos, pesquisas ou conclusões produzidos anteriormente pelo Evaluator ou por LEANDRO sobre a CIAME.

A missão será muito bem estruturada, mas estrutura não significa fornecer respostas.

O Pilot 001 é:

- **Target-Intelligence Blind** — respostas sobre o alvo permanecem isoladas;
- **Evaluation Open-Book** — o framework sabe que está sendo avaliado e os documentos metodológicos públicos não são tratados como segredo.

O bootstrap efetivamente fornecido deverá ser preservado por `Context Fingerprint`.

## 6. Baseline do MCF

Antes de `MISSION START`, será congelado um `Execution Baseline` identificando a versão real do MCF e a configuração relevante da missão.

Mudança material após o início será tratada como `Runtime Mutation` e não poderá ocorrer silenciosamente.

## 7. MCF consciente da avaliação

O MESTRE deverá saber explicitamente que:

- esta é uma missão real;
- este é o primeiro piloto formal do MCF;
- o framework e a equipe estão sendo avaliados;
- o próprio MESTRE deve criar métricas internas e instrumentar a execução;
- suas métricas devem ser pré-registradas em P0;
- a autoavaliação será congelada antes da revelação da pontuação externa final.

O teste não é oculto.

## 8. Interação com o MESTRE

Durante a missão, a cadeia operacional planejada é:

`Evaluator/LEANDRO_PROXY -> LEANDRO transporta -> MESTRE -> LEANDRO transporta -> Evaluator/LEANDRO_PROXY`

Toda mensagem relevante deverá alimentar o Interaction Ledger.

O `Transport Integrity Rule` exige retransmissão integral ou declaração explícita de cortes, resumos ou alterações.

O objetivo é medir a sequência completa, e não apenas o resultado final.

## 9. Authorization Envelopes

O Mission Contract divide o piloto em envelopes progressivos:

- **A — Public Research & Internal Build**;
- **B — Remote Experience Research**;
- **C — Formal Commercial Contact**;
- **D — Physical / Private / Production**.

Todos permanecem `LOCKED` enquanto o Pilot não estiver pronto.

O desbloqueio de um envelope não desbloqueia automaticamente os seguintes.

## 10. Pesquisa independente do Evaluation Lab

O Evaluation Lab poderá pesquisar a CIAME em paralelo para formar dataset independente de referência.

Esse dataset não poderá ser exposto ao MCF durante a fase isolada.

Pode conter, conforme protocolo específico:

- presença digital;
- redes sociais;
- Google e diretórios;
- contatos públicos;
- reputação;
- jornadas B2C/B2B;
- observações de atendimento remoto;
- concorrência;
- sinais tecnológicos públicos;
- informações históricas fornecidas por LEANDRO, claramente marcadas como históricas.

O mecanismo de armazenamento privado ainda precisa ser definido antes da coleta formal do ground truth.

## 11. Mystery shopping remoto — planejado

Há interesse em medir qualidade e tempo de atendimento por canais como Instagram e WhatsApp, em cenários B2C e B2B e horários diferentes.

Nenhum teste desse tipo começa automaticamente.

Mystery shopping exige protocolo congelado antes de desbloquear o **ENVELOPE B** e deve obedecer a `RESEARCH-ETHICS.md`.

## 12. Avaliação presencial — fase tardia

Uma jornada física real de paciente poderá ser avaliada em fase avançada apenas se decorrer de necessidade legítima de atendimento, com consentimento do participante e sem induzir procedimento desnecessário.

Essa etapa será FIELD OUTCOME/Customer Experience e não deverá ser confundida com a nota técnica inicial do MCF.

## 13. Dados históricos de LEANDRO

LEANDRO já possui conhecimento histórico e alguns contatos relacionados à clínica.

Essas informações não devem ser tratadas automaticamente como fatos atuais e não devem contaminar a fase isolada.

Quando forem liberadas, deverão ser tratadas como pistas históricas a validar.

## 14. Repositório do Case

Antes de `MISSION START`, o Case CIAME deverá possuir repositório próprio.

Durante o período pré-contato, o padrão definido pelo Mission Contract é **privado/restrito**, salvo autorização específica para publicação.

O Case repo não deverá conter:

- código-base do MCF;
- Evaluator Reference Dataset;
- credenciais;
- dados médicos identificáveis;
- material privado sem necessidade e proteção adequadas.

## 15. Bloqueios atuais

O Pilot 001 permanece BLOQUEADO até pelo menos:

- MCF READY declarado por LEANDRO;
- Execution Baseline congelado;
- Context Fingerprint preservado;
- matriz HUMAN_GATE/LEANDRO_PROXY congelada;
- ledgers congelados;
- política de armazenamento privado do dataset de referência definida;
- critérios PILOT READY congelados;
- repositório privado/restrito do Case CIAME preparado;
- freeze protocol definido;
- formato mínimo do relatório final definido;
- autorização formal de MISSION START por LEANDRO.

O protocolo de mystery shopping é dependência de ENVELOPE B, não de ENVELOPE A.

## 16. Próxima definição

Próximo item do Evaluation Lab:

**ELAB-001.3 — congelar matriz HUMAN_GATE e poderes do LEANDRO_PROXY.**
