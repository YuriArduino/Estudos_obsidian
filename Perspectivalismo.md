---
tipo: conceito
tags_principais: [perspectiva, identidade, sattig, metafisica]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia do Tempo", "Epistemologia"]
autores_associados: 
  - "[[Thomas Sattig]]"
oposto_dialetico:
  - "[[Absolutismo Ontológico]]"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Perspectivalismo

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A tese defendida por Thomas Sattig (2015) segundo a qual a identidade de um objeto pode ser avaliada de **diferentes perspectivas** sem que isso implique contradição. Sattig argumenta que podemos conciliar intuições conflitantes (ex: a estátua é idêntica aos átomos vs. a estátua é distinta dos átomos) relativizando a identidade à perspectiva adotada — a perspectiva do *objeto comum* vs a perspectiva do *objeto material*. O artigo (seção 4.3) menciona Sattig como proponente de uma visão que combina hilomorfismo com perspectivalismo.
* **Matriz de Origem:** Thomas Sattig (2015, *The Language and Reality of Time*) — mencionado no artigo (seção 4.3).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Relativizar a identidade a múltiplas perspectivas pode levar a uma fragmentação — cada objeto teria múltiplas identidades dependendo da perspectiva adotada.
* **Comportamento em Falta:** Ignorar as diferenças de perspectiva leva a paradoxos — como no caso da estátua e do lump, onde as intuições sobre identidade colidem.
* **Força Oposta (Antítese):** O **Absolutismo Ontológico** — a tese de que a identidade é absoluta e não depende de perspectiva (Kripke, Lewis).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Perspectivalismo permite que o Noösphera avalie a identidade de um `KnowledgeObject` de diferentes pontos de vista: a identidade *estrita* (id) e a identidade *frouxa* (sequência histórica). As diferentes perspectivas são compatíveis entre si.
* **Aplicação em Código / Estrutura de Dados:**
  - **Perspectiva do Conhecimento:** `KO` é uma identidade absoluta (id, tipo, leis).
  - **Perspectiva do Dado:** `KO` é uma sequência de `Representations` (payloads) ao longo do tempo.
  - Ambas as perspectivas são verdadeiras e não entram em conflito.
* **Relação com as Leis:**
  - **Lei II:** a identidade estrita é preservada na perspectiva do conhecimento.
  - **Lei X:** a identidade frouxa é preservada na perspectiva do dado (histórico).
  - **Lei IV:** a coerência é avaliada em ambas as perspectivas simultaneamente.