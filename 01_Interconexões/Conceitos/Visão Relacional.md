---
"type:": conceito
tags_principais:
  - logica
  - tempo
  - propriedades
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
autores_associados:
  - "[[David Lewis]]"
oposto_dialetico:
  - "[[Modificador Adverbial]]"
  - Operador Sentencial
implementado_em:
  - "[[Representation]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Visão Relacional

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Uma das soluções para o Problema dos Intrínsecos Temporários (seção 2.4 do artigo). Segundo a Visão Relacional, propriedades que parecem intrínsecas (ex: ser redondo) são, na verdade, **relacionais** — ou seja, são relações entre o objeto e o tempo. "Plate é redondo em $t_1$" significa que Plate está na relação *ser redondo em* com $t_1$. Lewis rejeita esta visão porque ela transforma propriedades intrínsecas em extrínsecas.
* **Matriz de Origem:** David Lewis (1986) — mencionado no artigo como uma solução que ele considera inadequada.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Transformar todas as propriedades intrínsecas em relacionais leva a uma ontologia onde nada é verdadeiramente intrínseco — tudo depende de sua relação com o tempo.
* **Comportamento em Falta:** Ignorar a visão relacional leva a dificuldades em explicar como algo pode ter propriedades incompatíveis em tempos diferentes.
* **Força Oposta (Antítese):** A visão de que propriedades intrínsecas são **não-relacionais** (a visão que Lewis defende).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Visão Relacional sugere que o `payload` de uma `Representation` não é uma propriedade intrínseca do `KnowledgeObject`, mas uma **relação** entre o objeto e o tempo (ou entre o objeto e o formato de serialização).
* **Aplicação em Código / Estrutura de Dados:**
  - O `payload` pode ser visto como uma relação triádica: `(KnowledgeObject, formato, tempo)`.
  - Isso permite que o objeto tenha diferentes `payloads` em diferentes tempos e formatos sem perder a identidade.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é preservada porque as relações não definem a essência do objeto.
  - **Lei IV (Coerência):** a coerência valida se a relação (payload, tempo, formato) é compatível com o tipo do objeto.