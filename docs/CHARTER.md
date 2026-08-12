# MCF Evaluation Lab — Charter v0.1

## 1. Missão

Criar uma camada independente, persistente e auditável para avaliar o desempenho do MCF em missões reais sem confundir execução, autoavaliação e julgamento externo.

## 2. Objetivos

O laboratório deve permitir responder, com evidências:

1. O MCF consegue executar uma missão real de ponta a ponta?
2. Qual é a qualidade objetiva do resultado produzido?
3. Quanto de intervenção humana foi necessário?
4. Quanto contexto inicial foi necessário para a missão funcionar corretamente?
5. O MCF coordenou agentes de forma útil ou apenas adicionou complexidade?
6. Os HUMAN_GATEs foram acionados corretamente?
7. O MCF consegue perceber e medir as próprias falhas?
8. Qual é a diferença entre a autoavaliação do MCF e a avaliação independente?
9. O resultado multiagente justifica o custo e a complexidade adicionais?
10. Quais mudanças no framework devem ser feitas antes do piloto seguinte?

## 3. Princípios

### 3.1 Avaliar antes de adaptar
Os critérios externos do piloto devem ser definidos e congelados antes da execução principal.

### 3.2 Execução e avaliação são funções diferentes
O MESTRE e os agentes podem criar métricas internas, mas não definem sozinhos o critério pelo qual o piloto será considerado aprovado.

### 3.3 Toda interação é dado experimental
Mensagens, esclarecimentos, HUMAN_GATEs, correções, retries, redirecionamentos e resgates devem ser registrados.

### 3.4 Memória de chat não é fonte canônica
Decisões persistentes devem ser registradas no GitHub.

### 3.5 Evidência acima de impressão
Avaliações devem distinguir fatos observáveis, métricas objetivas e julgamento qualitativo.

### 3.6 LEANDRO mantém autoridade final
Nenhum mecanismo de proxy remove a autoridade humana final de LEANDRO.

## 4. Produtos esperados

O laboratório deverá produzir, por piloto:

- Mission Contract;
- Evaluation Scorecard;
- Interaction Ledger;
- HUMAN_GATE Ledger;
- Evidence Index;
- Incident Log;
- Context Sufficiency Report;
- MCF Self-Evaluation;
- Independent Evaluation;
- Calibration Gap Report;
- Pilot Final Report;
- recomendações para a próxima versão do MCF.

## 5. Primeira aplicação

O primeiro piloto planejado é **Pilot 001 — CASE CIAME**.

A execução permanece bloqueada enquanto o MCF não estiver liberado por LEANDRO.
