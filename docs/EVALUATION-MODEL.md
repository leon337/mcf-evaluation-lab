# Evaluation Model v0.1

## 1. Estrutura de avaliação

O MCF será avaliado em três níveis complementares.

### Nível 1 — Telemetria objetiva

Métricas factuais coletadas a partir de logs e artefatos:

- agentes utilizados;
- handoffs;
- turnos de interação;
- duração por etapa quando disponível;
- retries;
- falhas;
- evidências coletadas;
- HUMAN_GATEs;
- intervenções E0–E5;
- intervenções H0–H5;
- retrabalho;
- artefatos produzidos;
- custo/tokens quando mensuráveis.

### Nível 2 — Avaliação independente

O Evaluator julga o resultado com base em critérios congelados previamente e nas evidências do piloto.

### Nível 3 — Avaliação de LEANDRO

LEANDRO avalia a utilidade prática e a confiança operacional, incluindo a pergunta central:

> Eu confiaria no MCF para executar outra missão empresarial real com este nível de autonomia?

## 2. Dimensões preliminares do scorecard externo

Os pesos abaixo são provisórios e devem ser congelados antes do Pilot 001.

- Investigação — 20%
- Qualidade das evidências — 15%
- Diagnóstico/raciocínio — 15%
- Coordenação multiagente — 15%
- Autonomia — 10%
- Governança — 10%
- Qualidade da solução — 10%
- Eficiência — 5%

## 3. Faixas preliminares

- `< 60` — falhou
- `60–69` — insuficiente
- `70–79` — piloto aceitável
- `80–89` — piloto forte
- `90–100` — piloto excepcional

Essas faixas ainda não estão congeladas.

## 4. Autoavaliação do MCF

O MESTRE deverá criar e registrar suas próprias métricas internas de missão.

O relatório final deve comparar:

`MCF Self-Evaluation` versus `Independent Evaluation`.

## 5. Calibration Gap

Definição preliminar:

`Calibration Gap = |nota da autoavaliação do MCF - nota da avaliação independente|`

O objetivo não é apenas obter nota alta, mas verificar se o MCF consegue reconhecer com precisão seu próprio desempenho e suas próprias falhas.

## 6. Context Sufficiency

O Pilot 001 também servirá para medir quanto contexto inicial uma missão MCF precisa.

Indicadores preliminares:

### CR — Clarification Rate
Quantidade e natureza dos esclarecimentos pedidos após o bootstrap inicial.

### CA — Context Accuracy
Proporção de interpretações iniciais corretas versus interpretações corrigidas posteriormente.

### CD — Context Debt
Retrabalho e bloqueios causados por informação ausente ou ambígua no contexto inicial.

### CU — Context Utilization
Quanto do contexto fornecido foi utilizado corretamente e sem necessidade de repetição.

### HR — Human Rescue
Quantidade de intervenções humanas necessárias para evitar falha material da missão.

## 7. Métricas de investigação

Quando houver dataset de referência independente, poderão ser usadas:

### Discovery Recall
Quanto dos fatos relevantes conhecidos pelo Evaluation Lab o MCF descobriu independentemente.

### Factual Precision
Quanto das afirmações factuais produzidas pelo MCF estava correto e adequadamente sustentado.

### Evidence Coverage
Quanto das conclusões materiais possui evidência rastreável.

## 8. Comparação de valor

O laboratório também deverá investigar se a abordagem multiagente produz benefício suficiente para justificar sua complexidade.

Pergunta de referência:

> O MCF produziu resultado materialmente melhor, mais confiável ou mais autônomo do que uma execução convencional por LEANDRO + um único agente?

No Pilot 001 essa comparação será inicialmente observacional. Experimentos A/B controlados deverão ser planejados separadamente para pilotos futuros.
