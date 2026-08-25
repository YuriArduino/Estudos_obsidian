---
tipo: conceito
tags_principais: [ontologia, identidade, sortais]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia da Linguagem"]
autores_associados: 
  - "[[Aristóteles]]"
  - "[[Peter Geach]]"
oposto_dialetico:
  - "[[Sortais de Fase]]"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Sortais de Substância

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Conceitos sortais que algo **não pode perder** sem deixar de existir. Um sortal de substância define a essência de um objeto — ele pertence àquela categoria enquanto existir. Exemplos: "ser humano", "ser cavalo", "ser estátua" (se a estátua for considerada uma substância). No artigo (seção 1), a distinção entre sortais de substância e fase é usada para discutir identidade e persistência.
* **Matriz de Origem:** Filosofia Analítica (P.F. Strawson, David Wiggins) com raízes em Aristóteles (a substância como categoria fundamental).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar sortais de substância leva a uma ontologia rígida — tudo seria essencial, e a mudança seria impossível.
* **Comportamento em Falta:** Não reconhecer sortais de substância leva a uma ontologia onde tudo é fase — nada tem essência, e a identidade se dissolve.
* **Força Oposta (Antítese):** Os **Sortais de Fase** — conceitos que algo pode perder sem deixar de existir (ex: "criança", "estudante").

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O `type` de um `KnowledgeObject` (ex: `Decision`, `Observation`) é um **sortal de substância** — o objeto não pode mudar de tipo sem perder sua identidade.
* **Aplicação em Código / Estrutura de Dados:**
  - Um `KnowledgeObject` do tipo `Decision` **não pode** se tornar uma `Observation` sem que sua identidade seja destruída e uma nova seja criada.
  - Mudar o `type` é uma **mudança essencial**, portanto viola a Lei II.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é definida pelo sortal de substância — mudar o sortal é violar a Lei II.
  - **Gramática:** a Gramática só permite relações que respeitem o sortal de substância das entidades envolvidas.