---
notion-id: 3b54f61f-7e76-8028-aa57-f21f77d66635
base: "[[Contratos de Materialização Arquitetural.base]]"
Atende qual Componente?:
  - "[[Observation Registry|Observation Registry]]"
Diretriz de Comportamento no Design: "Consolidação Aditiva (Append-Only Consolidation): A incorporação permanente de Observations previamente produzidas pelas Competencies, preservando sua identidade histórica e vedando qualquer sobrescrita, mutação ou exclusão de registros anteriores."
Materializa:
  - "[[Competency produz Observation|Competency produz Observation]]"
Proibição Arquitetural Absoluta (O que o verbo NÃO é): NÃO É uma atualização de tabela (UPDATE). É terminantemente vedada a sobrescrita histórica, a mutação de registros passados ou a exclusão disfarçada de mutação.
Contrato de Fronteira Acionado: Governado pelo Contrato de Persistência (testemunha mecânica irrevogável).
Tipo de Artefato: Schema do Grafo
---
