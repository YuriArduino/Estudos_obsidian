---
tipo: conceito
tags_principais:
  - identidade
  - logica
  - leibniz
status: sintetizado
areas_conceituais:
  - Lógica
  - Metafísica
autores_associados:
  - "[[Leibniz]]"
oposto_dialetico:
  - "[[Lei de Leibniz]]"
  - (Indiscernibilidade dos Idênticos)
implementado_em:
  - "[[Teste de Admissão Ontológica]]"
---

# Identidade dos Indiscerníveis

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Princípio que afirma que se duas coisas são qualitativamente idênticas (compartilham todas as suas propriedades), então elas são numericamente idênticas (são a mesma coisa). Ou seja, não pode haver duas coisas distintas que tenham exatamente as mesmas propriedades. Este princípio é o **inverso** da Lei de Leibniz (Indiscernibilidade dos Idênticos), e é mais controverso. O artigo (seção 1) menciona que Leibniz articulou ambos os princípios.
* **Matriz de Origem:** Gottfried Wilhelm Leibniz — mencionado na seção 1 do artigo como o princípio mais controverso da dupla leibniziana.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar a Identidade dos Indiscerníveis rigidamente leva a uma inflação ontológica — tudo que é parecido seria o mesmo, eliminando a distinção entre objetos diferentes (ex: duas bolas de bilhar idênticas).
* **Comportamento em Falta:** Ignorar completamente a Identidade dos Indiscerníveis impede de reconhecer quando duas representações são tão parecidas que podem ser consideradas redundantes.
* **Força Oposta (Antítese):** A **Lei de Leibniz (Indiscernibilidade dos Idênticos)** — que afirma o inverso: identidade implica indistinguibilidade, não o contrário.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade dos Indiscerníveis é um princípio que o Noösphera **não adota** como axioma, pois ele levaria a conclusões indesejadas (ex: duas `Representations` com o mesmo `payload` seriam o mesmo objeto).
* **Aplicação em Código / Estrutura de Dados:**
  - O Noösphera usa a **Lei de Leibniz** (Indiscernibilidade dos Idênticos) como critério de identidade, mas **não** a Identidade dos Indiscerníveis.
  - Duas `Representations` com o mesmo `payload` são qualitativamente idênticas, mas podem ser numericamente distintas (diferentes `ids`).
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é definida pelo `id` (numérica), não pela semelhança qualitativa.
  - **Teste de Admissão Ontológica (#1 — Universalidade):** a Universalidade não é definida por semelhança qualitativa, mas por pertinência ontológica.