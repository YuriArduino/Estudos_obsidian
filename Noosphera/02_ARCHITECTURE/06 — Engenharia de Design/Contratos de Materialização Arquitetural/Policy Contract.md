---
notion-id: 3b54f61f-7e76-8050-ab40-f91700643cb0
base: "[[Contratos de Materialização Arquitetural.base]]"
Atende qual Componente?:
  - "[[Policy Engine|Policy Engine]]"
Diretriz de Comportamento no Design: "Interceptação Normativa (Interceptive Validation): A aplicação estrita de Policies como guardas de fronteira na transição de estados."
Materializa:
  - "[[Policy restringe Relation|Policy restringe Relation]]"
  - "[[Policy restringe Representation|Policy restringe Representation]]"
Proibição Arquitetural Absoluta (O que o verbo NÃO é): NÃO É lógica de negócio acoplada. A restrição apenas avalia condições de passagem matemáticas, sem realizar transformações semânticas ou deduções cognitivas.
Contrato de Fronteira Acionado: Governado pelo Contrato de Coordenação Central (aplicando regras sobre a transição).
Tipo de Artefato: Interface de Serviço
---
