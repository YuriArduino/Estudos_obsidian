---
"type:": conceito
tags_principais:
  - identidade
  - logica
status: sintetizado
areas_conceituais:
  - Lógica
  - Metafísica
autores_associados:
  - "[[Leibniz]]"
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Identidade Numérica]]"
implementado_em:
  - "[[Representation]]"
---

# Identidade Qualitativa

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Duas coisas são **qualitativamente idênticas** quando se assemelham exatamente — ou seja, compartilham todas as suas propriedades qualitativas. Exemplo: duas bolas de bilhar perfeitamente idênticas são qualitativamente idênticas, mas não são a mesma coisa. A identidade qualitativa é uma relação de **semelhança**, não de mesmidade.
* **Matriz de Origem:** Distinção clássica na filosofia da identidade (usada no artigo da SEP, seção 1).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Tratar identidade qualitativa como suficiente para identidade leva a uma inflação ontológica — tudo que é parecido seria a mesma coisa, o que é falso.
* **Comportamento em Falta:** Ignorar a identidade qualitativa torna impossível reconhecer que duas coisas são indistinguíveis em suas propriedades, o que é útil para detectar redundâncias.
* **Força Oposta (Antítese):** A **Identidade Numérica** — ser a *mesma* coisa (um só objeto).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade Qualitativa é usada para comparar `Representations` — se duas representações têm o mesmo `payload` (mesmo conteúdo, mesmo formato), elas são qualitativamente idênticas. Mas isso **não** significa que são o mesmo objeto.
* **Aplicação em Código / Estrutura de Dados:**
  - Duas `Representations` com o mesmo `payload` (JSON idêntico) são qualitativamente idênticas, mas podem pertencer a `KnowledgeObjects` diferentes (identidade numérica distinta).
  - A comparação qualitativa é útil para detectar **redundâncias** ou **conflitos**.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade qualitativa não define a identidade do objeto; o `id` é a âncora numérica.
  - **Lei IV (Coerência):** a Lei IV pode usar a identidade qualitativa para verificar se duas representações são consistentes (ex: não têm payloads conflitantes para o mesmo `KO`).