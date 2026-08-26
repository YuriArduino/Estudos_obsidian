---
tipo: conceito
tags_principais: [modalidade, lewis, kripke]
status: "sintetizado"
areas_conceituais: ["Lógica Modal", "Metafísica"]
autores_associados: 
  - "[[David Lewis]]"
  - "[[Saul Kripke]]"
oposto_dialetico:
  - "[[Atualismo]]"
implementado_em: 
  - "[[Teoria dos Correspondentes]]"
---

# Mundos Possíveis

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Um mundo possível é uma maneira como o mundo **poderia ter sido** — uma alternativa completa à realidade atual. Na lógica modal, mundos possíveis são usados para avaliar proposições modais (necessidade e possibilidade). David Lewis defendeu o **Realismo Modal** (mundos possíveis são tão reais quanto o mundo atual), enquanto Saul Kripke usou mundos possíveis para formalizar a semântica da lógica modal, mas sem compromisso ontológico com sua existência real. O artigo (seção 4.5) menciona mundos possíveis no contexto da **Teoria dos Correspondentes**.
* **Matriz de Origem:** Lógica Modal (Kripke, 1959-1965); David Lewis (1986, *On the Plurality of Worlds*) — mencionado no artigo (seção 4.5).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso (Realismo Modal):** Aceitar que mundos possíveis são reais leva a uma inflação ontológica — há infinitos mundos, cada um tão real quanto o nosso.
* **Comportamento em Falta (Atualismo):** Rejeitar mundos possíveis leva a dificuldades em formalizar proposições modais (ex: "poderia ter sido") sem uma semântica adequada.
* **Força Oposta (Antítese):** O **Atualismo** — a tese de que apenas o mundo atual existe.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** Mundos Possíveis são usados para modelar **propriedades modais** no Noösphera — o que um `KnowledgeObject` *poderia* ter sido (ex: um `Decision` poderia ter sido uma `Observation`?).
* **Aplicação em Código / Estrutura de Dados:**
  - O Noösphera não adota o Realismo Modal de Lewis, mas usa a **Teoria dos Correspondentes** como ferramenta conceitual.
  - Propriedades modais (ex: "ser necessariamente um `Decision`") são avaliadas com referência a mundos possíveis abstratos.
* **Relação com as Leis:**
  - **Lei II:** a identidade é necessária — se `KO` é uma `Decision`, ele é `Decision` em todos os mundos possíveis.
  - **Lei IV:** a coerência é avaliada em relação a mundos possíveis (ex: um `payload` inválido em um mundo possível não afeta o mundo atual).