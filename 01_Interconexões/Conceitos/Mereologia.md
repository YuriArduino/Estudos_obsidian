---
"type:": conceito
tags_principais:
  - mereologia
  - partes
  - todo
  - ontologia
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
  - Matemática
autores_associados:
  - "[[Aristóteles]]"
  - "[[Peter van Inwagen]]"
  - "[[David Lewis]]"
  - "[[Theodore Sider]]"
oposto_dialetico:
  - "[[Nilismo Mereológico]]"
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Representation]]"
---

# Mereologia

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A teoria formal das **partes e todos** (do grego *meros*, "parte"). A mereologia estuda as relações de composição — como objetos podem ser compostos por partes, e como partes se relacionam com o todo que formam. Questões mereológicas incluem: quando duas ou mais coisas formam um todo? A relação de parte-todo é transitiva? Existe uma "soma" de quaisquer objetos (composição irrestrita)? O artigo (seção 4.3) menciona a mereologia (somas mereológicas) no contexto do perspectivalismo de Sattig.
* **Matriz de Origem:** Stanisław Leśniewski (fundador da mereologia formal), Peter van Inwagen, David Lewis, Theodore Sider.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso (Composição Irrestrita):** Qualquer coleção de objetos forma um todo — leva a uma inflação ontológica, onde há infinitos objetos (ex: a soma da minha orelha com a Torre Eiffel).
* **Comportamento em Falta (Nilismo Mereológico):** Não existem partes — apenas objetos simples (átomos) existem. Isso nega a noção de composição e inviabiliza estruturas complexas.
* **Força Oposta (Antítese):** O **Nilismo Mereológico** — a tese de que objetos compostos não existem; apenas objetos simples existem.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Mereologia fundamenta a relação entre `KnowledgeObject` e suas `Representations`. Um `KnowledgeObject` é um *todo* mereológico composto por suas `Representations` (partes), mas também por suas `Observations` e relações.
* **Aplicação em Código / Estrutura de Dados:**
  - A relação entre `KO` e `Representation` é uma relação mereológica: as `Representations` são *partes* que compõem o `KO`.
  - A **Lei X (Reconstruibilidade Histórica)** exige que a composição mereológica do `KO` (suas partes históricas) seja preservada.
* **Relação com as Leis:**
  - **Lei II:** a identidade do `KO` não é reduzida à soma de suas partes mereológicas (identidade estrita vs frouxa).
  - **Gramática:** as relações mereológicas (composição) são definidas pela Gramática.