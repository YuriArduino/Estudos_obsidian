---
"type:": conceito
tags_principais:
  - tempo
  - persistencia
  - lewis
status: sintetizado
areas_conceituais:
  - Filosofia do Tempo
  - Metafísica
autores_associados:
  - "[[David Lewis]]"
  - "[[Theodore Sider]]"
oposto_dialetico:
  - "[[Exdurantismo]]"
  - "[[Endurantismo]]"
implementado_em:
  - "[[Domínio Permanente]]"
  - "[[Observation]]"
---

# Perdurantismo

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A versão clássica do **Quadridimensionalismo**, segundo a qual um objeto persiste tendo **partes temporais** (estágios) em diferentes momentos do tempo. O objeto não é uma entidade tridimensional que "existe através do tempo" — ele é uma entidade quadridimensional que se estende no tempo, composta por suas partes temporais. O artigo (seção 4.5) apresenta o Perdurantismo (também chamado de "clássico") como a visão de Lewis, em contraste com o Exdurantismo (teoria dos estágios) de Sider e Hawley.
* **Matriz de Origem:** David Lewis (1986, *On the Plurality of Worlds*) — mencionado no artigo (seção 4.5) como a visão clássica do Quadridimensionalismo.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar o Perdurantismo a todos os objetos leva a uma ontologia onde tudo é extenso no tempo — o que pode ser contra-intuitivo para entidades que parecem instantâneas (ex: eventos).
* **Comportamento em Falta:** Ignorar o Perdurantismo leva a dificuldades em explicar como um objeto pode mudar de propriedades sem perder sua identidade (Problema dos Intrínsecos Temporários).
* **Força Oposta (Antítese):** O **Endurantismo** (3D) — objetos persistem como um todo, sem partes temporais. E o **[[Exdurantismo]]** — a versão alternativa do 4D onde objetos são estágios, não vermes.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Perdurantismo é a visão ontológica que fundamenta a persistência do `KnowledgeObject` no Noösphera: o objeto não é um ponto no tempo, mas a soma de toda a sua história — todas as suas `Representations` ao longo do tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - O `KnowledgeObject` é tratado como um "verme" 4D: seu `id` persiste, mas seu `payload` e suas `Representations` são partes temporais.
  - A consulta a um `KO` em um `timestamp` específico retorna a parte temporal correspondente (a `Representation` daquele momento).
* **Relação com as Leis:**
  - **Lei II:** a identidade é preservada através da continuidade das partes temporais.
  - **Lei X:** a reconstruibilidade histórica exige que todas as partes temporais (Representations) sejam registradas.