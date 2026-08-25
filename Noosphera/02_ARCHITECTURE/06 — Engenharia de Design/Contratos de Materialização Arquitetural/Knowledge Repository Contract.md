---
notion-id: 3b54f61f-7e76-805f-807b-ccfcd79e7f2a
base: "[[Contratos de Materialização Arquitetural.base]]"
Atende qual Componente?:
  - "[[Knowledge Repository|Knowledge Repository]]"
Diretriz de Comportamento no Design: "Acoplamento por Referência (Referential Coupling): A preservação da autonomia da identidade através de apontamentos topológicos imutáveis."
Materializa:
  - "[[KO possui Representation|KO possui Representation]]"
  - "[[Observation pertence a KO|Observation pertence a KO]]"
  - "[[KO relaciona-se com KO|KO relaciona-se com KO]]"
Proibição Arquitetural Absoluta (O que o verbo NÃO é): "NÃO É composição estrutural de dados. É proibido o aninhamento estrutural por valor na memória ativa (ex: objetos contendo objetos filhos que são deletados juntos em cascata)."
Contrato de Fronteira Acionado: Governado pelo Contrato de Persistência (como guardião de identidades exclusivas).
Tipo de Artefato: Schema do Grafo
---
