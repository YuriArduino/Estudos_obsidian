---
tipo: conceito
tags_principais: [logica, relacoes, identidade]
status: "sintetizado"
areas_conceituais: ["Lógica", "Matemática"]
autores_associados: 
  - "[[Leibniz]]"
oposto_dialetico:
  - "[[Assimetria]]"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[04 — Gramática Formal]]"
---

# Simetria

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedade de uma relação binária segundo a qual, se $aRb$, então $bRa$. A identidade é uma relação simétrica: se $a = b$, então $b = a$. O artigo (seção 2.2) afirma que a simetria da identidade segue da Lei de Leibniz — se $a$ tem a propriedade de ser idêntico a $b$, então $b$ tem a propriedade de ser idêntico a $a$. A simetria é uma das três propriedades que definem uma **Relação de Equivalência**.
* **Matriz de Origem:** Lógica Clássica (Leibniz) — formalizada na teoria das relações.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir simetria para todas as relações leva a conclusões indesejadas — "ser pai de" não é simétrico (se A é pai de B, B não é pai de A).
* **Comportamento em Falta:** Ignorar a simetria da identidade leva à impossibilidade de reconhecer que "a é idêntico a b" implica "b é idêntico a a".
* **Força Oposta (Antítese):** A **Assimetria** — relações que não obedecem à simetria (ex: "ser pai de").

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A simetria da identidade garante que, se `KO1 = KO2`, então `KO2 = KO1`. Isso é fundamental para a coerência do grafo.
* **Aplicação em Código / Estrutura de Dados:**
  - A Lei II (Invariância da Identidade) garante que a identidade é simétrica — o sistema não pode ter relações de identidade unidirecionais.
  - A Gramática pode definir relações assimétricas (ex: `Competency observa Representation` é assimétrica — a competência observa, não é observada), mas a identidade é sempre simétrica.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é simétrica — se `KO1 = KO2`, então `KO2 = KO1`.
  - **Gramática:** a simetria é uma propriedade que pode ser aplicada a outras relações, mas com restrições.