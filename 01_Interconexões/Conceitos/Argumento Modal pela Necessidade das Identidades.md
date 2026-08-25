---
tipo: conceito
tags_principais: [modalidade, identidade, logica]
status: "sintetizado"
areas_conceituais: ["Lógica Modal", "Metafísica"]
autores_associados: 
  - "[[Saul Kripke]]"
  - "[[Ruth Barcan Marcus]]"
oposto_dialetico:
  - "[[Identidades Contingentes]]"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Argumento Modal pela Necessidade das Identidades

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Um argumento lógico, desenvolvido por Saul Kripke e Ruth Barcan Marcus, que prova que a identidade é **necessária**. O argumento usa a Lei de Leibniz para mostrar que se `a = b`, então `a` e `b` compartilham todas as propriedades — incluindo a propriedade modal "ser necessariamente idêntico a `a`". Portanto, `b` também tem a propriedade de ser necessariamente idêntico a `a`, o que implica que `a = b` é necessário[reference:7][reference:8].
* **Matriz de Origem:** Saul Kripke (1971, *Identity and Necessity*; 1980, *Naming and Necessity*)[reference:9].

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar o argumento modal a todas as identidades pode levar a uma ontologia onde toda identidade é necessária, o que é contra-intuitivo para alguns casos (ex: "o homem na cadeira é o professor").
* **Comportamento em Falta:** Ignorar o argumento modal pode levar a uma ontologia onde a identidade é contingente — o que inviabiliza a noção de persistência.
* **Força Oposta (Antítese):** A **Identidade Contingente** — a tese de que a identidade pode ser contingente.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Argumento Modal fundamenta a **Lei II (Invariância da Identidade)** no Noösphera: se dois `KnowledgeObject` são idênticos, essa identidade é necessária e não pode ser contingente.
* **Aplicação em Código / Estrutura de Dados:**
  - O `id` de um `KnowledgeObject` é uma identidade necessária — não pode mudar ao longo do tempo.
  - A identidade é preservada através de todas as `Representations` e `Observations`.
* **Relação com as Leis:**
  - **Lei II:** a identidade é necessária — o `id` não pode mudar.
  - **Lei IV:** a coerência é avaliada com base em uma identidade necessária — se `KO1 = KO2`, essa identidade é necessária e suas propriedades devem ser compatíveis.