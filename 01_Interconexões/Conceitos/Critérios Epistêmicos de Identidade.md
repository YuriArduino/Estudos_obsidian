---
tipo: conceito
tags_principais: [identidade, epistemologia, mooney]
status: "sintetizado"
areas_conceituais: ["Epistemologia", "Metafísica"]
autores_associados: 
  - "[[Justin Mooney]]"
oposto_dialetico:
  - "[[Critérios Metafísicos de Identidade]]"
  - "[[Critérios Explicativos]]"
implementado_em: 
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Critérios Epistêmicos de Identidade

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Critérios que nos dizem **como saber** se dois objetos são idênticos, em vez de **o que faz** com que sejam idênticos (critérios metafísicos). No Fasalismo de Mooney, ele admite que não há um critério explicativo (metafísico) para a identidade do **Particular Fino** — apenas critérios epistêmicos, que nos permitem identificar o objeto no nível prático. O artigo (seção 4.8) menciona que Mooney oferece critérios epistêmicos, não explicativos.
* **Matriz de Origem:** Justin Mooney (2025a) — mencionado no artigo (seção 4.8).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Confiar apenas em critérios epistêmicos leva a uma ontologia onde a identidade é uma questão de "como sabemos", não de "o que é" — o que pode ser considerado insatisfatório para a metafísica.
* **Comportamento em Falta:** Ignorar critérios epistêmicos leva a uma ontologia onde a identidade é puramente metafísica, mas inacessível ao conhecimento humano.
* **Força Oposta (Antítese):** Os **Critérios Metafísicos (Explicativos)** — que definem o que faz com que dois objetos sejam idênticos.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Noösphera adota **critérios metafísicos** para a identidade (o `id` define a identidade). No entanto, os critérios epistêmicos são relevantes para a **Lei IV (Coerência)** — como *sabemos* que duas `Representations` são do mesmo `KO` (por exemplo, verificando o `id` e o `timestamp`).
* **Aplicação em Código / Estrutura de Dados:**
  - **Critério Metafísico:** `id` (define a identidade).
  - **Critério Epistêmico:** validação de que `Representation.payload` é compatível com `KO.type` (como sabemos que a representação é válida).
* **Relação com as Leis:**
  - **Lei IV:** a coerência é um critério epistêmico — ela nos permite verificar se a identidade está sendo respeitada, sem definir a identidade em si.