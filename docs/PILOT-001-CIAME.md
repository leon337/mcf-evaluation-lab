# Pilot 001 — CASE CIAME

Status: **PLANEJADO / EXECUÇÃO BLOQUEADA**

## 1. Identidade

O Pilot 001 será a primeira missão empresarial real utilizada para avaliar formalmente o MCF.

Alvo:

**CIAME — Centro Integrado de Atenção Médica**  
São Lourenço da Mata/PE.

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

O congelamento está registrado em:

`docs/checkpoints/CP-0002-SCORECARD-FREEZE.md`

## 4. Princípio de missão limpa

O MCF não deverá receber como contexto inicial os diagnósticos, pesquisas ou conclusões produzidos anteriormente pelo Evaluator ou por LEANDRO sobre a CIAME.

A missão deverá ser muito bem estruturada, mas estrutura não significa fornecer respostas.

O Mission Contract deverá especificar pelo menos:

- objetivo;
- alvo correto;
- escopo;
- resultado esperado;
- restrições;
- entregáveis;
- fontes permitidas;
- política de evidências;
- limites de atuação;
- HUMAN_GATE;
- definição de pronto;
- instrumentação mínima da missão.

## 5. MCF consciente da avaliação

O MESTRE deverá saber explicitamente que:

- esta é uma missão real;
- este é o primeiro piloto formal do MCF;
- o framework e a equipe estão sendo avaliados;
- o próprio MESTRE deve criar métricas internas e instrumentar a execução;
- a autoavaliação será posteriormente comparada à avaliação externa.

O teste não é oculto.

## 6. Interação com o MESTRE

Durante a missão, a cadeia operacional planejada é:

`Evaluator/LEANDRO_PROXY -> LEANDRO transporta -> MESTRE -> LEANDRO transporta -> Evaluator/LEANDRO_PROXY`

Toda mensagem relevante deverá alimentar o Interaction Ledger.

O objetivo é medir a sequência completa, e não apenas o resultado final.

## 7. Pesquisa independente do Evaluation Lab

O Evaluation Lab poderá pesquisar a CIAME em paralelo para formar um dataset independente de referência.

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

## 8. Mystery shopping remoto — planejado

Há interesse em medir qualidade e tempo de atendimento por canais como Instagram e WhatsApp, em cenários B2C e B2B e horários diferentes.

Nenhum teste desse tipo começa automaticamente.

O protocolo deverá ser congelado antes e obedecer a `RESEARCH-ETHICS.md`.

## 9. Avaliação presencial — fase tardia

Uma jornada física real de paciente poderá ser avaliada em fase avançada apenas se decorrer de necessidade legítima de atendimento, com consentimento do participante e sem induzir procedimento desnecessário.

Essa etapa será FIELD OUTCOME/Customer Experience e não deverá ser confundida com a nota técnica inicial do MCF.

## 10. Dados históricos de LEANDRO

LEANDRO já possui conhecimento histórico e alguns contatos relacionados à clínica.

Essas informações não devem ser tratadas automaticamente como fatos atuais e não devem contaminar a fase isolada.

Quando forem liberadas, deverão ser tratadas como pistas históricas a validar.

## 11. Bloqueios atuais

O Pilot 001 permanece BLOQUEADO até pelo menos:

- MCF READY declarado por LEANDRO;
- Mission Contract congelado;
- matriz HUMAN_GATE/LEANDRO_PROXY congelada;
- ledgers congelados;
- política de dataset de referência definida;
- protocolo de pesquisa remota definido;
- PILOT READY declarado.

## 12. Próxima definição

Próximo item do Evaluation Lab:

**criar e congelar o Mission Contract do Pilot 001 sem iniciar a missão.**
