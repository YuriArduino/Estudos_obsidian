---
tipo: conceito
tags_principais: [ontologia, mooney, substrato]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Lógica"]
autores_associados: 
  - "[[Justin Mooney]]"
oposto_dialetico:
  - "[[Substância]]"
  - "(com propriedades)"
implementado_em: 
  - "[[KnowledgeObject]]"
---

# Particular Fino

## 1. Definição e Matriz de Origem
* **Definição Teórica:** No Fasalismo de Mooney, o **Particular Fino** (*thin particular*) é o substrato subjacente que **não possui propriedades próprias**, mas é o portador das propriedades que o objeto adquire ou perde ao longo do tempo. Ele é uma construção lógica postulada por metafísicos para explicar a continuidade de um objeto através de mudanças de fase (ex: a argila que se torna estátua e depois argila novamente). O artigo (seção 4.8) menciona que Mooney considera o Particular Fino como aquilo que adquire e perde sortais de fase.
* **Matriz de Origem:** Justin Mooney (2023a) — mencionado no artigo (seção 4.8).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Postular particulares finos para tudo leva a uma ontologia onde objetos reais são substituídos por "portadores" vazios — uma visão que pode ser considerada artificial.
* **Comportamento em Falta:** Ignorar o particular fino leva a dificuldades em explicar como um objeto pode mudar de fase (ex: argila → estátua) sem perder sua continuidade.
* **Força Oposta (Antítese):** A **Substância com Propriedades** — a visão tradicional de que um objeto é uma substância que possui propriedades inerentes.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Particular Fino é análogo ao **substrato** de um `KnowledgeObject` — o que permanece quando todas as `Representations` mudam. No Noösphera, esse substrato é o `id` do objeto.
* **Aplicação em Código / Estrutura de Dados:**
  - O `id` do `KnowledgeObject` é o **Particular Fino** — ele não tem propriedades próprias, mas carrega as `Representations` e `Observations` ao longo do tempo.
  - O `type` e as `Leis` são propriedades que o Particular Fino adquire e perde? No Noösphera, não — elas são fixas (essenciais).
* **Relação com as Leis:**
  - **Lei II:** o `id` (Particular Fino) é invariante — ele define a continuidade do objeto.
  - **Lei IV:** a coerência valida se as propriedades adquiridas (payload) são compatíveis com o tipo fixo.