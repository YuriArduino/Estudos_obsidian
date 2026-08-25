---
notion-id: 3b54f61f-7e76-8028-98f4-cd33eb15024e
base: "[[Contratos de Materialização Arquitetural.base]]"
Atende qual Componente?:
  - "[[Event Bus|Event Bus]]"
Diretriz de Comportamento no Design: "Propagação Factual sem Comando (Commandless Propagation): A publicação de que um fato histórico foi consumado no ecossistema, sem direcionamento de alvo."
Materializa:
  - "[[Event anuncia Observation|Event anuncia Observation]]"
Proibição Arquitetural Absoluta (O que o verbo NÃO é): NÃO É uma chamada de função (RPC/Webhook ativo). O artefato anunciado não pode conter semântica de comando, intenção de execução ou esperar qualquer resposta.
Contrato de Fronteira Acionado: Governado pelo Contrato de Coordenação Central (que orquestra o barramento sem ler a semântica).
Tipo de Artefato: DTO de Transporte
---
