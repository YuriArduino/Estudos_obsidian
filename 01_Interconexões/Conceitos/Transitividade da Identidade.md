---
"type:": conceito
tags_principais:
  - identidade
  - logica
  - relacoes
status: sintetizado
areas_conceituais:
  - Lógica
  - Metafísica
autores_associados:
  - "[[Leibniz]]"
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Intransitividade]]"
  - "[[Transitividade da Identidade Temporária (TTI)]]"
implementado_em:
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[04 — Gramática Formal]]"
---

# Transitividade da Identidade

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedade fundamental da identidade segundo a qual, se $a = b$ e $b = c$, então $a = c$. A transitividade é uma das três propriedades que definem uma **Relação de Equivalência** (junto com reflexividade e simetria). O artigo (seção 2.2) afirma que a transitividade da identidade segue da **Lei de Leibniz** — se $a = b$ e $b = c$, então $b$ tem a propriedade de ser idêntico a $c$, e $a$ (sendo idêntico a $b$) também deve ter essa propriedade, logo $a = c$.
* **Matriz de Origem:** Lógica Clássica (Aristóteles, Leibniz) — formalizada na teoria das relações.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir transitividade para todas as relações leva a conclusões indesejadas — por exemplo, se "ser amigo de" fosse transitivo, amigos de amigos seriam amigos, o que não é verdade.
* **Comportamento em Falta:** Ignorar a transitividade da identidade leva a paradoxos — como no **Navio de Teseu**, onde Replacement e Reassembly poderiam ambos ser idênticos ao original sem serem idênticos entre si.
* **Força Oposta (Antítese):** A **Intransitividade** — relações que não obedecem à transitividade (ex: "ser pai de"). Ou a **Transitividade da Identidade Temporária (TTI)** — uma versão relativizada ao tempo proposta por Gallois.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A transitividade da identidade garante que, se `KO1 = KO2` e `KO2 = KO3`, então `KO1 = KO3`. Isso é fundamental para a coerência do grafo de conhecimento — o sistema não pode ter cadeias de identidade quebradas.
* **Aplicação em Código / Estrutura de Dados:**
  - A **Lei II (Invariância da Identidade)** garante que a identidade é transitiva — o sistema não pode ter um `KO` que seja igual a um segundo, e este igual a um terceiro, sem que o primeiro seja igual ao terceiro.
  - A transitividade é o que permite que o sistema infira identidades indiretas.
* **Relação com as Leis:**
  - **Lei II:** a identidade é transitiva — `KO1 = KO2` e `KO2 = KO3` implica `KO1 = KO3`.
  - **Gramática:** a transitividade é uma propriedade que pode ser aplicada a outras relações (ex: `KO relaciona-se com KO` pode ser transitiva?), mas a identidade é sempre transitiva.