---
"type:": conceito
tags_principais:
  - ontologia
  - metafisica
  - estrutura
status: sintetizado
areas_conceituais:
  - Ontologia
  - Filosofia da Mente
autores_associados:
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Materialismo Reducionista]]"
implementado_em:
  - "[[KnowledgeObject]]"
---

# Hilomorfismo

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Doutrina que sustenta que todo objeto físico (substância) é composto por dois princípios co-principais: a **Matéria** (ὕλη, hylé) — o substrato potencial, e a **Forma** (μορφή, morphé) — a estrutura atualizante que define *o que* a coisa é. A identidade da coisa reside na Forma, não na Matéria.
* **Matriz de Origem:** Metafísica Aristotélica.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Priorizar excessivamente a *Forma* leva ao idealismo (Platônico), onde a matéria é desprezada e a identidade se torna uma abstração desconectada dos dados.
* **Comportamento em Falta:** Priorizar excessivamente a *Matéria* leva ao reducionismo, onde a identidade é apenas a soma das partes (ex: o navio é apenas as tábuas), incapaz de lidar com mudanças estruturais.
* **Força Oposta (Antítese):** O **Reducionismo Físico** (tudo é matéria) e o **Idealismo Puro** (tudo é forma).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** É o conceito estruturante que separa o *dado* (payload) da *estrutura* (tipo + leis). Permite que o sistema trate o dado como algo volátil e a estrutura como algo estável.
* **Aplicação em Código / Estrutura de Dados:** 
  - `KnowledgeObject` = **Substância** (composta de Matéria + Forma).
  - `Representation.payload` = **Matéria** (pode ser JSON, Protobuf, etc.).
  - `KnowledgeObject.type` + `Leis` = **Forma** (define o que é aquilo).
* **Relação com as Leis:** A **Lei IV (Coerência)** é o mecanismo que valida se a Matéria (payload) está em conformidade com a Forma (tipo/leis) no instante da instanciação.