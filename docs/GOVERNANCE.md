# Governance v0.1

## 1. Papéis

### LEANDRO
Autoridade humana final do experimento.

Responsabilidades reservadas:

- liberar o MCF para o Pilot 001;
- autorizar contato real com a CIAME quando exigido;
- autorizar uso de credenciais, gastos, publicação, produção ou acesso privado;
- aprovar mudanças materiais de escopo;
- decidir sobre encerramento ou aceite final do piloto.

### MESTRE
Orquestrador operacional do MCF durante o piloto.

O MESTRE deverá saber explicitamente que:

- esta será uma missão real;
- esta será também uma avaliação formal do MCF;
- ele e a equipe devem instrumentar a própria execução;
- métricas internas não substituem a avaliação independente.

### EVALUATOR
Camada externa ao MCF responsável por protocolo, observação, medição, classificação de interações, auditoria e relatório.

O Evaluator não deve fornecer dicas silenciosas para fazer o MCF passar no teste.

### LEANDRO_PROXY
Papel operacional delegado ao Evaluator para responder apenas decisões previamente autorizadas pela política de HUMAN_GATE.

O proxy:

- não se apresenta falsamente como sendo LEANDRO;
- registra toda decisão tomada;
- atua somente dentro do escopo delegado;
- escala decisões críticas para LEANDRO.

## 2. Canal de interação com o MESTRE

Durante o Pilot 001, a interação seguirá a cadeia:

`Evaluator/Proxy -> LEANDRO transporta mensagem -> MESTRE -> LEANDRO transporta resposta -> Evaluator/Proxy`

O objetivo é garantir que o Evaluation Lab receba a sequência completa das interações e possa medir:

- total de turnos;
- pedidos de esclarecimento;
- repetição de instruções;
- informação adicional fornecida;
- HUMAN_GATEs;
- correções;
- redirecionamentos;
- resgates;
- retrabalho.

## 3. Classificação preliminar de intervenção do Evaluator

- **E0 — retransmissão:** sem ajuda adicional.
- **E1 — resposta prevista:** resposta diretamente coberta pelo contrato da missão.
- **E2 — contexto adicional necessário:** informação legítima não disponível inicialmente.
- **E3 — correção:** o Evaluator corrige interpretação ou erro do MCF.
- **E4 — redirecionamento:** o Evaluator precisa alterar o curso adotado pelo MCF.
- **E5 — resgate operacional:** sem a intervenção, a missão ficaria bloqueada ou materialmente comprometida.

E3–E5 devem pesar negativamente na autonomia observada.

## 4. Classificação preliminar de HUMAN_GATE

- **H0 — nenhum gate necessário.**
- **H1 — gate delegado e previsto.**
- **H2 — esclarecimento humano legítimo.**
- **H3 — correção humana.**
- **H4 — redirecionamento humano.**
- **H5 — resgate humano.**

## 5. Gates delegáveis ao LEANDRO_PROXY

Podem ser delegados, desde que previstos no Mission Contract:

- continuação de pesquisa pública;
- seleção entre alternativas equivalentes e reversíveis;
- repetição de testes;
- revisão e reorganização de artefatos;
- avanço entre etapas já autorizadas.

## 6. Gates exclusivos de LEANDRO

Exigem decisão direta de LEANDRO:

- contato real com a CIAME quando ainda não autorizado pelo protocolo;
- compromissos comerciais;
- envio de proposta;
- gastos;
- uso de credenciais privadas;
- acesso a sistemas privados;
- implantação em produção;
- publicação pública;
- mudança material de escopo;
- decisões jurídicas ou de alto risco;
- tratamento excepcional de informação sensível;
- encerramento e aceite final do piloto.

## 7. Separação entre avaliação e proxy

Embora possam ser operados pelo mesmo ChatGPT, `EVALUATOR` e `LEANDRO_PROXY` são papéis logicamente separados.

Toda ação do proxy deve ser registrada em ledger próprio e considerada na avaliação de autonomia. O Evaluator não pode usar o papel de proxy para orientar ocultamente o MCF.

## 8. Protocolo de continuidade LEANDRO ↔ Evaluator

A continuidade normal da conversa entre LEANDRO e o Assistant/Evaluator é regida por:

`docs/CONVERSATION-CONTINUITY-PROTOCOL-v1.1.md`

Esse protocolo:

- organiza opções de continuidade da conversa;
- exige consulta ao estado canônico quando disponível;
- torna explícita a recomendação e consequência de cada caminho;
- fornece resposta copiável para LEANDRO;
- não substitui HUMAN_GATE;
- não amplia poderes do LEANDRO_PROXY;
- não concede autorização automática para ações operacionais.

Escolher uma `Continuity Option` não deve ser contabilizado como HUMAN_GATE, salvo quando a própria decisão também satisfizer formalmente os critérios de um HUMAN_GATE previsto pela governança.

A versão v1.1 foi congelada em:

`docs/checkpoints/CP-0004-CONVERSATION-CONTINUITY-FREEZE.md`
