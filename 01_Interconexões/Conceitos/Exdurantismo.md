---
"type:": conceito
tags_principais:
  - tempo
  - persistencia
  - sider
  - hawley
status: sintetizado
areas_conceituais:
  - Filosofia do Tempo
  - Metafísica
autores_associados:
  - "[[Theodore Sider]]"
  - "[[Katherine Hawley]]"
oposto_dialetico:
  - "[[Perdurantismo]]"
  - "[[Endurantismo]]"
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Representation]]"
---

# Exdurantismo

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Uma versão alternativa do **Quadridimensionalismo**, também chamada de **Teoria dos Estágios** (*Stage Theory*). Segundo o Exdurantismo, objetos não são "vermes" 4D (como no Perdurantismo), mas **estágios** (partes temporais instantâneas). A persistência de um objeto através do tempo é explicada por relações de **correspondente** (counterpart) entre estágios — o estágio de hoje é um correspondente do estágio de ontem. O artigo (seção 4.5) menciona Sider e Hawley como defensores do Exdurantismo, e Hawley é associada ao termo.
* **Matriz de Origem:** Theodore Sider (2002, *Four Dimensionalism*), Katherine Hawley (2001) — mencionado no artigo (seção 4.5).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar o Exdurantismo a todos os objetos leva a uma ontologia onde não há objetos contínuos — apenas estágios instantâneos relacionados por correspondência.
* **Comportamento em Falta:** Ignorar o Exdurantismo leva a dificuldades em explicar a persistência sem recorrer a "vermes" 4D (Perdurantismo).
* **Força Oposta (Antítese):** O **[[Perdurantismo]]** — onde objetos são vermes 4D, e o **Endurantismo** — onde objetos persistem como um todo 3D.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Exdurantismo oferece uma visão alternativa para o Noösphera: o `KnowledgeObject` não é um "verme" 4D (soma de todas as Representações), mas cada `Representation` é um **estágio** do objeto. A identidade ao longo do tempo é uma relação de correspondente entre estágios.
* **Aplicação em Código / Estrutura de Dados:**
  - No Exdurantismo, o `KnowledgeObject` é a `Representation` atual. O histórico de versões é uma cadeia de correspondentes (Representations anteriores).
  - A identidade é preservada pela relação de correspondente (ex: `version_id` ou `previous_representation_id`).
* **Relação com as Leis:**
  - **Lei II:** a identidade é preservada pela continuidade da relação de correspondente entre estágios.
  - **Lei X:** a reconstruibilidade histórica exige que os estágios (Representations) sejam registrados para que a cadeia de correspondentes seja rastreável.