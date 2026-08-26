---
tipo: conceito
tags_principais: [tempo, persistencia, metafisica]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica"]
autores_associados: 
  - "[[David Lewis]]"
  - "[[Theodore Sider]]"
  - "[[Katherine Hawley]]"
oposto_dialetico:
  - "[[Partes Espaciais]]"
  - "(como modelo único)"
implementado_em: 
  - "[[Observation]]"
  - "[[Domínio Permanente]]"
---

# Partes Temporais

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Partes de um objeto que existem em diferentes momentos do tempo. Na visão **Quadridimensionalista** (Perdurantismo), um objeto não é uma entidade tridimensional que persiste através do tempo, mas sim uma entidade quadridimensional composta por partes temporais (estágios) em cada momento de sua existência. A parte temporal mais curta e instantânea é chamada de **estágio** (stage). O artigo (seção 2.4 e 4.5) usa Partes Temporais para resolver o Problema dos Intrínsecos Temporários e os puzzles diacrônicos.
* **Matriz de Origem:** David Lewis (1986), *On the Plurality of Worlds*; também defendido por Theodore Sider e Katherine Hawley.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar partes temporais desnecessariamente leva a uma inflação ontológica — cada objeto tem infinitas partes, o que pode tornar o sistema complexo demais.
* **Comportamento em Falta:** Ignorar partes temporais impede a compreensão de como um objeto pode mudar ao longo do tempo sem perder sua identidade.
* **Força Oposta (Antítese):** A visão **Tridimensionalista** (Endurantismo) — objetos persistem como um todo, sem partes temporais.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** As Partes Temporais são a justificativa ontológica para tratar cada `Representation` de um `KnowledgeObject` como uma "fatia" do objeto em um determinado momento. O `KnowledgeObject` é a soma de todas as suas `Representations` ao longo do tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Observation` de um `KnowledgeObject` pode ser vista como uma **parte temporal** — um registro do estado do objeto naquele momento.
  - O `KnowledgeObject` não é um ponto no tempo, mas uma **sequência histórica** de partes temporais.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é preservada através da continuidade das partes temporais — o objeto é a soma de sua história.
  - **Lei X (Reconstruibilidade Histórica):** a reconstrução histórica é possível porque cada parte temporal é registrada como uma `Observation`.