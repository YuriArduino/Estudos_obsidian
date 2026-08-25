---
tipo: conceito
tags_principais: [logica, relacoes, identidade]
status: "sintetizado"
areas_conceituais: ["Lógica", "Matemática"]
autores_associados: 
  - "[[Leibniz]]"
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Intransitividade]]"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[04 — Gramática Formal]]"
---

# Transitividade

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedade de uma relação binária segundo a qual, se $aRb$ e $bRc$, então $aRc$. A identidade é uma relação transitiva: se $a = b$ e $b = c$, então $a = c$. O artigo (seção 2.2) afirma que a transitividade da identidade segue da Lei de Leibniz. A transitividade é uma das três propriedades que definem uma **Relação de Equivalência** (junto com reflexividade e simetria).
* **Matriz de Origem:** Lógica Clássica (Aristóteles, Leibniz) — formalizada na teoria das relações.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir transitividade para todas as relações leva a conclusões indesejadas — por exemplo, se "ser amigo de" fosse transitivo, amigos de amigos seriam amigos, o que não é verdade.
* **Comportamento em Falta:** Ignorar a transitividade da identidade leva a paradoxos — ex: no Navio de Teseu, a identidade poderia ser quebrada.
* **Força Oposta (Antítese):** A **Intransitividade** — relações que não obedecem à transitividade (ex: "ser pai de").

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A transitividade da identidade garante que, se `KO1 = KO2` e `KO2 = KO3`, então `KO1 = KO3`. Isso é fundamental para a coerência do grafo de conhecimento.
* **Aplicação em Código / Estrutura de Dados:**
  - A Lei II (Invariância da Identidade) garante que a identidade é transitiva — o sistema não pode ter cadeias de identidade quebradas.
  - A Gramática pode definir outras relações que não são transitivas (ex: `Competency observa Representation` não é transitiva), mas a identidade é sempre transitiva.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é transitiva — se `KO1 = KO2` e `KO2 = KO3`, então `KO1 = KO3`.
  - **Gramática:** a transitividade é uma propriedade que pode ser aplicada a outras relações, mas com restrições.