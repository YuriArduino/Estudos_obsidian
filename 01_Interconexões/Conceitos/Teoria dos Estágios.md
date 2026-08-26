---
tipo: conceito
tags_principais: [tempo, persistencia, exdurantismo]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica"]
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

# Teoria dos Estágios

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Sinônimo de **Exdurantismo**. A Teoria dos Estágios (Stage Theory) é uma versão do Quadridimensionalismo segundo a qual **objetos são estágios** (partes temporais instantâneas), não "vermes" 4D. A persistência de um objeto através do tempo é explicada por relações de **correspondente** (counterpart) entre estágios — o estágio de hoje é um correspondente do estágio de ontem. O artigo (seção 4.5) menciona que Sider defende a Teoria dos Estágios como uma visão sobre os significados de nossa linguagem de objetos ordinários, enquanto Hawley a considera a ontologia correta.
* **Matriz de Origem:** Theodore Sider (2002, *Four Dimensionalism*), Katherine Hawley (2001) — mencionado no artigo (seção 4.5).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar a Teoria dos Estágios a todos os objetos leva a uma ontologia onde não há objetos contínuos — apenas estágios instantâneos relacionados por correspondência.
* **Comportamento em Falta:** Ignorar a Teoria dos Estágios leva a dificuldades em explicar a persistência sem recorrer a "vermes" 4D (Perdurantismo) ou a objetos 3D (Endurantismo).
* **Força Oposta (Antítese):** O **[[Perdurantismo]]** — onde objetos são vermes 4D, e o **Endurantismo** — onde objetos persistem como um todo 3D.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Teoria dos Estágios oferece uma visão alternativa para o Noösphera: o `KnowledgeObject` não é um "verme" 4D (soma de todas as Representações), mas cada `Representation` é um **estágio** do objeto. A identidade ao longo do tempo é uma relação de correspondente entre estágios.
* **Aplicação em Código / Estrutura de Dados:**
  - Na Teoria dos Estágios, o `KnowledgeObject` é a `Representation` atual. O histórico de versões é uma cadeia de correspondentes (Representations anteriores).
  - A identidade é preservada pela relação de correspondente (ex: `version_id` ou `previous_representation_id`).
* **Relação com as Leis:**
  - **Lei II:** a identidade é preservada pela continuidade da relação de correspondente entre estágios.
  - **Lei X:** a reconstruibilidade histórica exige que os estágios (Representations) sejam registrados para que a cadeia de correspondentes seja rastreável.