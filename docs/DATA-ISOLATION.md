# Data Isolation Policy v0.1

## 1. Problema

O Evaluation Lab precisa preservar evidências independentes para comparar com o MCF. Ao mesmo tempo, o repositório `leon337/mcf-evaluation-lab` é público no momento da fundação.

Se o ground truth da CIAME for armazenado aqui, o próprio MCF poderá encontrá-lo durante uma investigação pública e contaminar a fase Blind.

## 2. Regra

**O Evaluator Reference Dataset da CIAME NÃO será armazenado neste repositório público enquanto o Blind Pilot 001 depender de isolamento.**

Este repositório pode armazenar:

- protocolo;
- governança;
- métricas;
- scorecards;
- templates;
- decisões metodológicas;
- checkpoints que não revelem respostas do alvo;
- relatórios finais depois que o freeze adequado permitir publicação.

Não deve armazenar antes do freeze:

- lista de fatos descobertos sobre a CIAME;
- análise detalhada das redes sociais;
- ranking de problemas encontrados;
- ground truth usado para recall/precision;
- contatos privados ou históricos;
- scripts de mystery shopping ainda sigilosos quando sua exposição puder afetar o teste;
- evidências privadas.

## 3. Armazenamento futuro do dataset

Antes de iniciar coleta sistemática de ground truth, LEANDRO e o Evaluator deverão escolher um mecanismo isolado, por exemplo:

- repositório privado separado;
- armazenamento local criptografado;
- outro repositório privado de evidências;
- solução equivalente com acesso restrito.

A decisão deverá ser registrada antes da coleta formal.

## 4. Acesso do MCF

Durante a fase Blind, o Mission Contract deverá proibir explicitamente o MCF de usar o Evaluation Lab ou qualquer dataset do Evaluator como fonte de respostas sobre a CIAME.

Mesmo com essa proibição, o isolamento físico/lógico dos dados continua preferível à confiança apenas em instruções.
