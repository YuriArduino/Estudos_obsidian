---
"type:": conceito
tags_principais:
  - logica
  - tempo
  - proposicoes
status: sintetizado
areas_conceituais:
  - Lógica
  - Filosofia do Tempo
autores_associados:
  - "[[David Lewis]]"
oposto_dialetico:
  - "[[Modificador Adverbial]]"
  - "[[Visão Relacional]]"
implementado_em:
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Operador Sentencial

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Uma das soluções para o Problema dos Intrínsecos Temporários (seção 2.4 do artigo). Segundo esta visão, 'em $t_1$' e 'em $t_2$' devem ser entendidos como operadores sentenciais: "em $t_1$ é verdade que Plate é redondo" e "em $t_2$ é verdade que Plate é quadrado". Isso é análogo a operadores modais: assim como "é possível que Plate seja redondo" é consistente com "é possível que Plate seja quadrado", os operadores temporais também permitem consistência.
* **Matriz de Origem:** Lógica Modal e Lógica Temporal — mencionado no artigo (seção 2.4) como uma das alternativas à visão relacional.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar operadores sentenciais a todas as proposições leva a uma proliferação de operadores — cada tempo, cada modalidade exigiria um operador diferente.
* **Comportamento em Falta:** Ignorar operadores sentenciais leva a dificuldades em expressar proposições temporais sem modificar a estrutura da proposição.
* **Força Oposta (Antítese):** O **Modificador Adverbial** — que modifica a maneira como a propriedade é instanciada, não a proposição como um todo.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Operador Sentencial sugere que a validade de uma `Representation` pode ser expressa como "em $t$, é verdade que este `payload` representa este `KnowledgeObject`". A verdade é indexada ao tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Observation` pode ser vista como uma proposição indexada ao tempo: "em $t$, foi observado que o `KnowledgeObject` X tinha o `payload` Y".
  - A validade de uma `Representation` pode ser avaliada no tempo em que foi produzida.
* **Relação com as Leis:**
  - **Lei IV (Coerência):** a coerência pode ser avaliada com operadores temporais — "em $t$, a `Representation` é coerente com o tipo do objeto".
  - **Lei X (Reconstruibilidade Histórica):** a reconstrução histórica exige que as proposições sobre o passado sejam avaliadas com operadores temporais adequados.