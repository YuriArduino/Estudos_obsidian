---
tipo: conceito
tags_principais: [ontologia, identidade, linguagem]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia da Linguagem"]
autores_associados: 
  - "[[Peter Geach]]"
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Conceitos Não-Sortais]]"
  - "(ex: matéria, cor)"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[04 — Gramática Formal]]"
---

# Conceitos Sortais

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Conceitos que respondem à pergunta "o que é isto?" fornecendo um critério de identidade e individuação para objetos. Um conceito sortal permite contar objetos daquela categoria (ex: "quantos cavalos?"). Exemplos: "cavalo", "estátua", "pessoa", "copo". Conceitos não-sortais, como "ouro" ou "vermelho", não fornecem um critério de contagem ou identidade. O artigo (seção 1 e 4.2) distingue entre **sortais de substância** (ex: "humano") e **sortais de fase** (ex: "criança").
* **Matriz de Origem:** Filosofia Analítica (P.F. Strawson, David Wiggins), com raízes em Aristóteles (a distinção entre substância e acidente). Geach usou sortais para formular sua tese da Identidade Relativa.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar sortais desnecessariamente leva a uma inflação ontológica — cada categoria teria seu próprio critério de identidade, fragmentando o sistema.
* **Comportamento em Falta:** Não reconhecer sortais leva a uma ontologia onde tudo é um amontoado de propriedades sem critério de identidade, inviabilizando a noção de "mesmo objeto".
* **Força Oposta (Antítese):** Os **Conceitos Não-Sortais** — como "matéria" ou "cor", que descrevem propriedades sem fornecer critério de identidade.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O `type` de um `KnowledgeObject` (ex: `Decision`, `Observation`) funciona como um **sortal** — define o critério de identidade e as operações admissíveis para aquele tipo de objeto.
* **Aplicação em Código / Estrutura de Dados:**
  - **Sortais no Noösphera:** `KnowledgeObject.type` (ex: `Decision`, `Observation`) define o que conta como "o mesmo" objeto dentro daquela categoria.
  - **Sortais de Substância:** `KnowledgeObject.type` é um sortal de substância (o objeto não pode mudar de tipo sem perder a identidade).
  - **Sortais de Fase:** `Representation.format` (ex: JSON, Protobuf) pode ser visto como um sortal de fase — o objeto pode mudar de formato sem perder a identidade.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é definida pelo sortal (tipo) — mudar de sortal é uma mudança essencial, portanto viola a Lei II.
  - **Gramática:** a Gramática só permite relações que respeitem os sortais das entidades conectadas.