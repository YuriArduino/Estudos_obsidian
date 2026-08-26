---
tipo: conceito
tags_principais: [identidade, logica, sortais]
status: "sintetizado"
areas_conceituais: ["Lógica", "Metafísica"]
autores_associados: 
  - "[[Peter Geach]]"
oposto_dialetico:
  - "[[Identidade Absoluta]]"
implementado_em: 
  - "[[04 — Gramática Formal]]"
  - "[[KnowledgeObject]]"
---

# Identidade Relativa

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Tese defendida por Peter Geach (e outros) segundo a qual não existe uma relação única e absoluta de identidade. Em vez de perguntar "a é idêntico a b?", deve-se perguntar "a é o mesmo **F** que b?" — onde F é um **sortal** (conceito de tipo). Isso permite que a seja o mesmo F que b, mas não o mesmo G que b. Formalmente: a e b são o mesmo F, mas não o mesmo G. O artigo (seção 4.2) usa o exemplo do copo e do copo truncado para ilustrar.
* **Matriz de Origem:** Peter Geach (1967), *Reference and Generality*. Também defendido por David Griffin.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Relativizar a identidade a todos os sortais possíveis leva a uma fragmentação — cada objeto teria múltiplas identidades, inviabilizando a noção de um objeto único.
* **Comportamento em Falta:** Insistir na identidade absoluta (Kripke) pode levar a paradoxos em casos de mudança de partes ou de tipo.
* **Força Oposta (Antítese):** A **Identidade Absoluta** — a tese de que a identidade é uma relação única, reflexiva, simétrica e transitiva, independente de sortais (Kripke, Lewis).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade Relativa sugere que a identidade de um `KnowledgeObject` não é absoluta, mas depende do `type` (sortal). Dois objetos podem ser o mesmo `Decision` (mesmo `id`), mas não o mesmo `Observation` — mesmo que compartilhem o mesmo `payload`.
* **Aplicação em Código / Estrutura de Dados:**
  - A pergunta "KO1 é idêntico a KO2?" só faz sentido se especificarmos o **tipo**: "KO1 é o mesmo `Decision` que KO2?"
  - Isso permite que um objeto seja o mesmo em um contexto (ex: mesma `Decision`) e distinto em outro (ex: diferente `Observation`).
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é relativa ao tipo — a Lei II protege a identidade dentro de um tipo, mas não necessariamente através de tipos diferentes.
  - **Gramática:** a Gramática deve especificar quais relações são válidas entre diferentes tipos, considerando a relatividade da identidade.