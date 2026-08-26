---
tipo: conceito
tags_principais: [tempo, persistencia, exdurantismo]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica"]
autores_associados: 
  - "[[David Lewis]]"
  - "[[Theodore Sider]]"
  - "[[Katherine Hawley]]"
oposto_dialetico:
  - "[[Vermes 4D]]" 
  - "[[Perdurantismo]]"
implementado_em: 
  - "[[Representation]]"
  - "[[Observation]]"
---

# Estágios (Partes Temporais)

## 1. Definição e Matriz de Origem
* **Definição Teórica:** As partes temporais mais curtas e instantâneas de um objeto na visão **Quadridimensionalista**. Um **estágio** é uma fatia do objeto em um momento específico do tempo. Na **Teoria dos Estágios** (Exdurantismo), os objetos *são* estágios — e a persistência através do tempo é explicada por relações de correspondente entre estágios (ex: o estágio de hoje é correspondente ao estágio de ontem). No **Perdurantismo**, os estágios são partes do "verme" 4D. O artigo (seção 2.4 e 4.5) menciona estágios como a solução de Lewis para o Problema dos Intrínsecos Temporários.
* **Matriz de Origem:** David Lewis (1986), Theodore Sider (2002), Katherine Hawley (2001) — mencionado no artigo (seção 2.4 e 4.5).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Fragmentar o objeto em infinitos estágios leva a uma ontologia onde a identidade é pulverizada — o objeto "verdadeiro" desaparece.
* **Comportamento em Falta:** Ignorar estágios leva a dificuldades em explicar como um objeto pode ter propriedades diferentes em tempos diferentes (Problema dos Intrínsecos Temporários).
* **Força Oposta (Antítese):** Os **Vermes 4D (Perdurantismo)** — onde o objeto é o verme todo, e os estágios são apenas partes.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** Os Estágios são a justificativa ontológica para tratar cada `Representation` de um `KnowledgeObject` como uma "fatia" do objeto em um determinado momento. O `KnowledgeObject` é a soma de seus estágios (Representations e Observations) ao longo do tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Representation` é um **estágio** do `KnowledgeObject`.
  - Na perspectiva do **Exdurantismo** (Teoria dos Estágios), o `KO` *é* a `Representation` atual, e o histórico é uma cadeia de correspondentes.
  - Na perspectiva do **Perdurantismo**, o `KO` *é* a soma de todos os seus estágios.
* **Relação com as Leis:**
  - **Lei II:** a identidade é preservada pela continuidade dos estágios (representações).
  - **Lei X:** a reconstruibilidade histórica exige que cada estágio (Representation) seja registrado.