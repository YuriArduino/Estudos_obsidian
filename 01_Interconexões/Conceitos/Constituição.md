---
"type:": conceito
tags_principais:
  - metafisica
  - identidade
  - ontologia
status: sintetizado
areas_conceituais:
  - Metafísica
  - Filosofia do Tempo
autores_associados:
  - "[[Lynne Rudder Baker]]"
  - "[[Kit Fine]]"
  - "[[Thomson]]"
oposto_dialetico:
  - "[[Identidade]]"
  - Constituição vs Identidade
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Representation]]"
---

# Constituição

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A relação entre um objeto e aquilo que o compõe materialmente, mas que não é idêntico a ele. A Teoria da Constituição (defendida por Baker, Fine e outros) sustenta que a constituição é uma relação **não-idêntica** e **não-simétrica**: um objeto pode ser constituído por outro sem ser idêntico a ele. Exemplo: a estátua é constituída pelo lump de argila, mas a estátua não é idêntica ao lump (pois têm propriedades modais diferentes). O artigo (seção 4.1) discute a constituição como uma solução para os puzzles diacrônicos: Cup nunca é idêntico a Tcup, mas em um tempo posterior Cup é constituído por Tcup.
* **Matriz de Origem:** Lynne Rudder Baker (2002), Kit Fine, Judith Jarvis Thomson — mencionado no artigo (seção 4.1) como uma das principais soluções para os puzzles diacrônicos.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar a constituição a todos os casos leva a uma ontologia onde a identidade é rara e tudo é constituído por algo — uma "visão de múltiplas coisas" (metaphysical multiple vision) que muitos consideram absurda.
* **Comportamento em Falta:** Ignorar a distinção entre constituição e identidade leva a paradoxos — como no caso da estátua e do lump, onde seriam forçados a ser idênticos, apesar de terem propriedades modais diferentes.
* **Força Oposta (Antítese):** A **Identidade** — a tese de que constituição é, na verdade, identidade (Noonan 1993), ou que a distinção é desnecessária.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Constituição é o conceito que separa o `KnowledgeObject` (a identidade) de suas `Representations` (a matéria). O `KnowledgeObject` é *constituído* por suas `Representations`, mas não é *idêntico* a elas.
* **Aplicação em Código / Estrutura de Dados:**
  - `Representation.payload` = **Matéria** (constitui o objeto).
  - `KnowledgeObject` = **Forma/Identidade** (não é idêntico ao payload).
  - A relação entre `KO` e suas `Representations` é uma relação de **constituição**, não de identidade.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a constituição não viola a identidade — o `KO` permanece o mesmo mesmo quando suas `Representations` mudam (constituição variável, identidade invariante).
  - **Lei IV (Coerência):** a Lei IV valida se a matéria (constituição) está em conformidade com a forma (identidade).

## 4. Conflito: Constituição vs Identidade
A grande tensão filosófica (mencionada no artigo, seção 4.1) é se a constituição é uma relação distinta da identidade ou se, em última análise, constituição *é* identidade. No Noösphera, adotamos a visão de que constituição **não é identidade** — pois as `Representations` podem mudar sem que a identidade do `KnowledgeObject` seja afetada.