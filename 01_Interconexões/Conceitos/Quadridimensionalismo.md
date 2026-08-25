---
tipo: conceito
tags_principais:
  - tempo
  - persistencia
  - metafisica
status: sintetizado
areas_conceituais:
  - Filosofia do Tempo
  - Metafísica
autores_associados:
  - "[[Lewis (David)]]"
  - "[[Sider (Theodore)]]"
  - "[[Hawley (Katherine)]]"
oposto_dialetico:
  - "[[Tridimensionalismo]]"
  - "(Endurantismo)"
  - "[[Presentismo]]"
implementado_em:
  - "[[Domínio Permanente]]"
  - "[[Observation]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Quadridimensionalismo

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Tese metafísica segundo a qual objetos são estendidos no tempo assim como no espaço — ou seja, são entidades quadridimensionais (3D espaciais + 1D temporal). Um objeto persiste tendo **partes temporais** (estágios) em diferentes momentos. O Quadridimensionalismo resolve o Problema dos Intrínsecos Temporários (Lewis) e os puzzles diacrônicos (Navio de Teseu, Estátua e Lump). O artigo (seções 2.4, 4.5) apresenta o Quadridimensionalismo como uma das principais soluções para a identidade através do tempo.
* **Matriz de Origem:** David Lewis (1986), *On the Plurality of Worlds*; também defendido por Theodore Sider e Katherine Hawley.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar o Quadridimensionalismo rigidamente leva a uma visão onde tudo é extenso no tempo — o que pode ser contra-intuitivo para entidades que parecem instantâneas (ex: eventos).
* **Comportamento em Falta:** Ignorar o Quadridimensionalismo leva a dificuldades para explicar como um objeto pode mudar de propriedades sem perder sua identidade.
* **Força Oposta (Antítese):** O **Tridimensionalismo (Endurantismo)** — objetos persistem como um todo, sem partes temporais. E o **Presentismo** — apenas o presente existe.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Quadridimensionalismo é a visão ontológica que fundamenta a persistência do `KnowledgeObject`. O objeto não é um ponto no tempo; é a soma de sua história — todas as suas `Representations` e `Observations` ao longo do tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - O `KnowledgeObject` é tratado como uma entidade 4D: seu `id` persiste, mas seu `payload` e suas `Representations` são partes temporais.
  - A consulta a um `KnowledgeObject` em um `timestamp` específico retorna a parte temporal correspondente (a `Representation` daquele momento).
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é preservada através da continuidade das partes temporais.
  - **Lei X (Reconstruibilidade Histórica):** a visão 4D exige que toda a história do objeto seja registrada para que sua identidade seja plenamente compreendida.