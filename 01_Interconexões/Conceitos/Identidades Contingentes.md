---
"type:": conceito
tags_principais:
  - identidade
  - modalidade
  - logica
status: sintetizado
areas_conceituais:
  - Lógica Modal
  - Metafísica
autores_associados:
  - "[[Saul Kripke]]"
  - "[[Ruth Barcan Marcus]]"
oposto_dialetico:
  - "[[Identidade Necessária]]"
implementado_em:
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Identidades Contingentes

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A tese de que uma sentença de identidade pode ser verdadeira em um mundo possível e falsa em outro — ou seja, que a identidade pode ser **contingente**. Exemplo: "a mesa na outra sala é minha favorita" — poderia não ter sido. Kripke e Marcus argumentam que, na verdade, identidades são **necessárias**, não contingentes[reference:2][reference:3].
* **Matriz de Origem:** Saul Kripke (1971, *Identity and Necessity*; 1980, *Naming and Necessity*) e Ruth Barcan Marcus — eles argumentam que a identidade é necessária, e que a aparência de contingência vem da ambiguidade dos designadores[reference:4][reference:5].

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aceitar identidades contingentes pode levar a uma ontologia onde a identidade é instável — o que inviabiliza a noção de persistência.
* **Comportamento em Falta:** Rejeitar completamente identidades contingentes pode ignorar casos onde a identidade parece genuinamente contingente (ex: "o ganhador da eleição é o candidato X").
* **Força Oposta (Antítese):** A **Identidade Necessária** — a tese de que se `a = b` é verdadeiro, então é necessariamente verdadeiro (Kripke, Marcus)[reference:6].

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Noösphera adota a visão de Kripke: a identidade é **necessária**. Se um `KnowledgeObject` é idêntico a outro (`KO1 = KO2`), essa identidade é necessária e não pode ser contingente.
* **Aplicação em Código / Estrutura de Dados:**
  - O `id` de um `KnowledgeObject` é uma identidade necessária — não pode ser "às vezes" o mesmo.
  - A **Lei II (Invariância da Identidade)** garante que a identidade é necessária e invariante.
* **Relação com as Leis:**
  - **Lei II:** a identidade é necessária — não pode ser contingente.
  - **Lei IV:** a coerência é avaliada com base em uma identidade necessária — se `KO1 = KO2`, então essa identidade é necessária e suas propriedades devem ser compatíveis.