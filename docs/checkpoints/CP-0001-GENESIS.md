# CP-0001 — Genesis Checkpoint

**Data:** 2026-08-12  
**Status:** CANÔNICO PARA CONTINUIDADE DO EVALUATION LAB  
**Pilot 001:** ainda não iniciado

## 1. Motivo deste checkpoint

LEANDRO criou e entregou um repositório vazio para que o Evaluation Lab passe a ter memória persistente independente de chats.

A preocupação central é evitar perda de contexto e retrabalho. A partir deste ponto, o GitHub deve registrar decisões operacionais importantes do laboratório.

## 2. Topologia aprovada

Três projetos devem permanecer separados:

1. `leon337/multiagent-collaboration-framework` — o MCF.
2. `leon337/mcf-evaluation-lab` — avaliação independente.
3. futuro repositório próprio para o CASE CIAME.

O Case CIAME não deve ser armazenado dentro do repositório do framework.

## 3. Situação do MCF

O MCF ainda não está liberado para trabalho real.

Responsabilidade atual de LEANDRO: concluir o framework até que possa ser explicitamente declarado pronto para o Pilot 001.

Enquanto isso, LEANDRO + Evaluator podem preparar em paralelo:

- Evaluation Lab;
- protocolo;
- scorecard;
- missão inicial;
- políticas de HUMAN_GATE;
- metodologia de pesquisa;
- pesquisa independente isolada.

## 4. Pilot 001 escolhido

O primeiro trabalho real planejado é o **CASE CIAME**, referente à CIAME de **São Lourenço da Mata/PE**.

Uma pesquisa anterior confundiu a empresa com uma homônima de Aracaju/SE. Essa associação está descartada e não deve ser reutilizada.

## 5. Finalidade múltipla do CASE CIAME

O projeto deverá servir simultaneamente como:

- primeiro case comercial de LEANDRO nessa metodologia;
- primeiro projeto real do MCF;
- teste de fogo do framework;
- ambiente para amadurecer uma metodologia de diagnóstico empresarial;
- fonte de métricas para melhorar o MCF;
- estudo sobre quanto contexto inicial deve ser entregue em futuras missões.

## 6. Estratégia comercial

A intenção é não iniciar oferecendo genericamente desenvolvimento de site ou perguntando à empresa o que ela precisa.

A estratégia é construir previamente diagnóstico, mapa de oportunidades, solução proposta, protótipos/demonstrações, testes e business case suficientemente maduros para uma apresentação de alto valor.

Contato comercial formal permanece bloqueado até gate apropriado de LEANDRO.

## 7. Avaliação independente

Este chat/instância do ChatGPT assumirá o papel de **Evaluator** do Pilot 001.

O MCF não julgará sozinho o próprio sucesso.

A avaliação terá pelo menos três níveis:

- telemetria objetiva;
- avaliação independente;
- avaliação final de utilidade/confiança por LEANDRO.

O MESTRE deverá também produzir métricas internas, permitindo comparar autoavaliação com avaliação externa.

## 8. MESTRE consciente do teste

O MESTRE e a equipe não serão avaliados secretamente.

A missão deverá informar que:

- é o primeiro projeto real do MCF;
- o framework está sendo formalmente testado;
- o MESTRE deve instrumentar e medir a própria execução;
- haverá avaliação independente posterior.

## 9. Comunicação integral com o MESTRE

LEANDRO decidiu que toda interação operacional entre o lado humano e o MESTRE deverá passar pelo Evaluation Lab para que o número e o tipo de interações sejam mensuráveis.

Fluxo previsto:

`Evaluator/LEANDRO_PROXY -> LEANDRO transporta -> MESTRE -> LEANDRO transporta -> Evaluator/LEANDRO_PROXY`

Toda mensagem relevante deverá ser registrada e classificada.

## 10. LEANDRO_PROXY

O Evaluator poderá assumir um papel delegado para responder gates operacionais previamente autorizados, reduzindo a necessidade de interromper LEANDRO para decisões reversíveis.

Por integridade de governança, o proxy não fingirá literalmente ser LEANDRO. O MCF deverá saber quando uma resposta vem de autoridade delegada.

Decisões críticas continuam exclusivas de LEANDRO.

## 11. Medição de intervenção

Foi aprovada a ideia de classificar interações do Evaluator de E0 a E5 e intervenções humanas de H0 a H5, distinguindo simples retransmissão de correção, redirecionamento ou resgate.

Quanto mais intervenções de correção/resgate forem necessárias, menor a autonomia demonstrada pelo framework.

## 12. Contexto inicial da missão

Por ser o primeiro trabalho em produção real, a missão deverá ser muito bem estruturada.

Objetivo do primeiro piloto:

> testar se o MCF executa bem uma missão profissionalmente especificada, não se consegue adivinhar intenções ausentes.

A missão poderá fornecer objetivo, escopo, restrições, fontes permitidas, deliverables, definição de pronto e governança, mas não deve entregar o diagnóstico pronto.

O piloto medirá o Context Sufficiency para ajudar a criar futuramente um `MCF Mission Bootstrap Standard`.

## 13. Blind Start

O MCF deverá começar sem receber as conclusões de pesquisa que LEANDRO + Evaluator descobrirem paralelamente.

O conhecimento independente será reservado para comparação posterior.

Poderá existir uma segunda fase `Human Augmented`, após freeze, em que conhecimento histórico de LEANDRO seja revelado seletivamente e tratado como pista a verificar.

## 14. Conhecimento histórico de LEANDRO

LEANDRO já prestou serviços de TI para a CIAME aproximadamente 8–10 anos atrás e possui algum conhecimento e contatos históricos da organização.

O estado atual dessas relações não deve ser presumido. O laboratório não armazenará dados privados de contato neste repositório público.

Essas informações poderão ser usadas somente na fase adequada do piloto.

## 15. Pesquisa independente da CIAME

LEANDRO + Evaluator poderão pesquisar a empresa antes do MCF estar pronto, mas os achados específicos deverão formar um dataset isolado do MCF.

Como este repositório é público, o ground truth da CIAME não deve ser armazenado aqui antes do momento adequado.

## 16. Teste de atendimento remoto

Foi proposta uma avaliação de experiência por canais como Instagram e WhatsApp, incluindo cenários B2C e B2B e diferentes horários.

Métricas pretendidas incluem:

- tempo até primeira resposta;
- clareza;
- utilidade;
- capacidade de resolver/encaminhar;
- follow-up;
- diferenças por canal, horário e tipo de demanda.

Esse teste deverá usar protocolo prévio, baixo impacto e controles éticos. Não será iniciado antes de o protocolo ser congelado.

## 17. Possível etapa presencial

Como etapa final futura, poderá ser analisada uma jornada real de paciente na clínica física.

LEANDRO sugeriu que a experiência de um familiar possa eventualmente servir como observação, caso exista atendimento real e consentido. Não será criado atendimento desnecessário apenas para gerar dados.

## 18. Objetivos de medição já identificados

O Evaluation Lab deverá medir pelo menos:

- investigação;
- qualidade e cobertura das evidências;
- diagnóstico;
- coordenação multiagente;
- autonomia;
- governança;
- qualidade da solução;
- eficiência;
- número de handoffs;
- falhas e retries;
- retrabalho;
- total e tipo de intervenções externas;
- total e tipo de HUMAN_GATEs;
- Context Sufficiency;
- Discovery Recall;
- Factual Precision;
- Evidence Coverage;
- Calibration Gap entre autoavaliação e avaliação independente;
- valor adicional do MCF comparado a uma abordagem convencional.

## 19. Estado ao fechar CP-0001

- MCF: **EM FINALIZAÇÃO POR LEANDRO**.
- Evaluation Lab: **FUNDAÇÃO v0.1 INICIADA**.
- Pilot 001 CIAME: **PLANEJAMENTO; EXECUÇÃO BLOQUEADA**.
- Case CIAME repo: **AINDA NÃO CRIADO**.
- pesquisa independente: **PERMITIDA, desde que isolada do MCF**.
- testes de atendimento: **SOMENTE PLANEJAMENTO**.
- avaliação presencial: **FUTURA**.
- interação com MESTRE: **NÃO INICIADA**.

## 20. Próximas decisões, ainda não congeladas

1. scorecard externo definitivo e pesos;
2. critérios objetivos de PASS/FAIL;
3. Mission Contract do Pilot 001;
4. matriz completa de HUMAN_GATE e poderes do LEANDRO_PROXY;
5. formato de Interaction Ledger;
6. mecanismo privado para Evaluator Reference Dataset;
7. protocolo de mystery shopping;
8. critérios de MCF READY;
9. critérios de PILOT READY;
10. criação e governança do repositório do Case CIAME.

---

Este checkpoint registra a compreensão consolidada do projeto no instante de fundação do repositório e deve ser usado para reconstruir a continuidade sem depender da memória do chat.
