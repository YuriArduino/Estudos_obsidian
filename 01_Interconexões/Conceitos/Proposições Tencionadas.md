---
tipo: conceito
tags_principais: [tempo, logica, proposicoes]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Lógica"]
autores_associados: 
  - "[[Sally Haslanger]]"
  - "[[Edward Jonathan Lowe]]"
  - "[[Arthur Prior]]"
oposto_dialetico:
  - "[[Proposições Atemporais]]"
implementado_em: 
  - "[[Observation]]"
  - "[[Lei X — A Reconstruibilidade Histórica]]"
---

# Proposições Tencionadas

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Proposições que carregam **tempo intrínseco** — ou seja, seu conteúdo inclui uma referência temporal (passado, presente, futuro). Exemplo: "Plate é redondo" (no presente) vs "Plate foi redondo" (no passado). O artigo (seção 2.4) menciona proposições tencionadas como uma solução para o Problema dos Intrínsecos Temporários: a mudança de uma propriedade intrínseca corresponde a uma mudança no **tempo** da proposição que a atribui.
* **Matriz de Origem:** Arthur Prior (lógica temporal, *tensed logic*), Sally Haslanger (1989)[reference:14], Edward Jonathan Lowe (1987) — mencionados no artigo como defensores da abordagem das proposições tencionadas.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar proposições tencionadas desnecessariamente leva a uma proliferação de proposições — cada tempo exigiria uma proposição diferente, tornando o sistema complexo.
* **Comportamento em Falta:** Ignorar proposições tencionadas leva a dificuldades em expressar proposições sobre o passado e o futuro sem modificar a estrutura da proposição.
* **Força Oposta (Antítese):** As **Proposições Atemporais** — proposições que não carregam referência temporal intrínseca (ex: "2 + 2 = 4" é atemporal)[reference:15].

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** As Proposições Tencionadas fundamentam a ideia de que cada `Observation` é uma proposição indexada ao tempo: "em $t$, foi observado que `KnowledgeObject` X tinha `payload` Y". O tempo é parte da proposição.
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Observation` carrega um `timestamp` que a torna uma proposição tencionada.
  - A **Lei X (Reconstruibilidade Histórica)** exige que as proposições sobre o passado sejam preservadas como proposições tencionadas.
* **Relação com as Leis:**
  - **Lei X:** a reconstrução histórica exige que as proposições tencionadas sejam preservadas para que o passado seja reconstruível.
  - **Lei IV:** a coerência pode ser avaliada em proposições tencionadas — "em $t$, a `Representation` era coerente com o tipo do objeto".