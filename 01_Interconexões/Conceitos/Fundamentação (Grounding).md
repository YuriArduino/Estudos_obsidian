---
tipo: conceito
tags_principais: [metafisica, fundamentacao, explicacao]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia da Ciência"]
autores_associados: 
  - "[[Kit Fine]]"
  - "[[Jonathan Schaffer]]"
oposto_dialetico:
  - "[[Fatos Brutos]]"
implementado_em: 
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Fundamentação (Grounding)

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A relação metafísica de **fundamentação** (*grounding*) é uma relação de dependência ontológica que explica como fatos de nível superior são determinados por fatos de nível mais básico. No artigo (seção 4.1), a objeção do *grounding* é usada contra a Teoria da Constituição: se a estátua e o lump de argila têm exatamente os mesmos átomos organizados da mesma forma, como pode a argila ser *esmagável* e a estátua não? A diferença de propriedades modais precisaria de uma fundamentação (uma explicação ontológica) que a Constituição não consegue fornecer satisfatoriamente.
* **Matriz de Origem:** Metafísica Analítica Contemporânea (Kit Fine, Jonathan Schaffer) — mencionado no artigo (seção 4.1).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir fundamentação para tudo leva a uma regressão infinita — cada fato precisaria de um fato mais básico para fundamentá-lo.
* **Comportamento em Falta:** Aceitar fatos brutos sem fundamentação leva a uma ontologia onde coisas acontecem sem explicação, o que é teoricamente insatisfatório.
* **Força Oposta (Antítese):** Os **Fatos Brutos** — fatos que não precisam de fundamentação (defendidos por Wasserman, Bennett, Kurtsal no artigo).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Fundamentação é usada para justificar por que uma `Representation` (payload) pode mudar sem afetar a identidade do `KnowledgeObject`. A identidade é **fundamentada** na estrutura do objeto (type + leis), enquanto o `payload` é apenas matéria.
* **Aplicação em Código / Estrutura de Dados:**
  - A identidade do `KO` é **fundamentada** no `id` e no `type` (essência).
  - O `payload` é uma propriedade acidental que não fundamenta a identidade — pode mudar sem comprometer o que o objeto *é*.
* **Relação com as Leis:**
  - **Lei II:** a identidade é fundamentada na essência do objeto, não em suas representações acidentais.
  - **Lei IV:** a coerência é fundamentada na conformidade do `payload` com o tipo e as leis do objeto.