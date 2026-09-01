---
"type:": conceito
tags_principais:
  - ontologia
  - espaco
  - coincidencia
status: sintetizado
areas_conceituais:
  - Metafísica
  - Filosofia do Espaço
autores_associados:
  - "[[Thomson]]"
  - "[[David Lewis]]"
  - "[[Kit Fine]]"
oposto_dialetico:
  - "[[Unicidade Espacial]]"
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Representation]]"
---

# Coincidência

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Fenômeno pelo qual dois ou mais objetos distintos ocupam exatamente o mesmo espaço no mesmo tempo. Exemplo clássico: a estátua e o lump de argila — são dois objetos diferentes (a estátua é uma forma, a argila é a matéria), mas ocupam o mesmo lugar enquanto a estátua existe. O artigo (seção 4.1, 4.5, 4.7) discute a coincidência como um problema central para a identidade, com soluções como a Teoria da Constituição, o Quadridimensionalismo e a Plenitude Modal.
* **Matriz de Origem:** Judith Jarvis Thomson (1983, 1998), David Lewis, Kit Fine — mencionado no artigo (seção 4.5) como um dos custos da visão da coincidência.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar objetos coincidentes leva a uma **inflação ontológica** — se estátua e argila são dois, por que não três (ex: a estátua, a argila, e o "objeto de arte"?)?
* **Comportamento em Falta:** Ignorar a coincidência leva a uma ontologia onde a identidade é determinada apenas pela posição no espaço — o que é falso (ex: a estátua e a argila são diferentes, mesmo ocupando o mesmo espaço).
* **Força Oposta (Antítese):** A **Unicidade Espacial** — a tese de que dois objetos não podem ocupar o mesmo espaço no mesmo tempo.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Coincidência é análoga à coexistência de múltiplas `Representations` para o mesmo `KnowledgeObject`. Duas `Representations` (ex: JSON e Protobuf) podem "ocupar" o mesmo espaço lógico (o mesmo `KO`), mas são manifestações diferentes.
* **Aplicação em Código / Estrutura de Dados:**
  - Um `KnowledgeObject` pode ter múltiplas `Representations` com o mesmo `payload` (coincidência qualitativa), mas são numericamente distintas (diferentes `representations_id`).
  - A coincidência é resolvida pelo `id` do `KO` — todas as `Representations` apontam para o mesmo `id`, portanto são do mesmo objeto.
* **Relação com as Leis:**
  - **Lei II:** a identidade do `KO` é definida pelo `id`, não pela coincidência espacial (ou lógica).
  - **Lei IV:** a coerência valida se as `Representations` coincidentes são compatíveis entre si e com o tipo do objeto.