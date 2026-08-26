---
tipo: conceito
tags_principais: [identidade, logica, sortais]
status: "sintetizado"
areas_conceituais: ["Lógica", "Metafísica"]
autores_associados: 
  - "[[Aristóteles]]"
  - "[[Peter Geach]]"
  - "[[Saul Kripke]]"
oposto_dialetico:
  - "[[Identidade como Fato Bruto]]"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[KnowledgeObject]]"
---

# Critério de Identidade

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Um conjunto de condições necessárias e suficientes para determinar se duas ocorrências de um objeto (em tempos diferentes ou em contextos diferentes) são a mesma coisa. O critério de identidade é sempre relativo a um **sortal** (conceito de tipo) — por exemplo, o critério para "mesmo cavalo" é diferente do critério para "mesma estátua". O artigo (seção 1) menciona que sortais de substância vêm acompanhados de um critério de identidade.
* **Matriz de Origem:** Filosofia Analítica (P.F. Strawson, David Wiggins), com raízes em Aristóteles.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir um critério de identidade para tudo leva a uma proliferação de critérios — cada tipo de objeto teria seu próprio critério, fragmentando o sistema.
* **Comportamento em Falta:** Não ter um critério de identidade leva à impossibilidade de decidir se duas coisas são a mesma, inviabilizando a coerência do sistema.
* **Força Oposta (Antítese):** A **Identidade como Fato Bruto** — a identidade é uma relação primitiva que não precisa de critério (Kripke).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Critério de Identidade é o que define como o sistema decide se dois `KnowledgeObject` (ou duas `Representations`) são a mesma coisa. No Noösphera, o critério é: **mesmo `id` = mesma identidade**.
* **Aplicação em Código / Estrutura de Dados:**
  - O critério de identidade para `KnowledgeObject` é o `id` — se dois objetos têm o mesmo `id`, são o mesmo objeto.
  - O critério de identidade para `Representation` é a combinação de `id` do `KnowledgeObject` + `timestamp` (ou `version`).
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a Lei II estabelece que o critério de identidade (`id`) é invariante.
  - **Lei IV (Coerência):** a Lei IV usa o critério de identidade para validar se as propriedades do objeto são coerentes.