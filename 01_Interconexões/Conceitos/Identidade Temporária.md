---
tipo: conceito
tags_principais: [identidade, tempo, logica]
status: "sintetizado"
areas_conceituais: ["Lógica", "Filosofia do Tempo"]
autores_associados: 
  - "[[Gallois (Andre)]]"
  - "[[Myro (George)]]"
oposto_dialetico:
  - "[[Identidade Necessária]]"
  - "(Kripke)"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[Observation]]"
---

# Identidade Temporária

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Tese segundo a qual dois objetos podem ser idênticos em um tempo e distintos em outro. Exemplo: Cup (copo com alça) e Tcup (copo sem alça) são distintos antes da quebra, mas idênticos depois (segundo a teoria). O artigo (seção 4.6) discute a Identidade Temporária como uma solução radical para os puzzles diacrônicos, defendida por George Myro e Andre Gallois. Eles propõem a **Transitividade da Identidade Temporária (TTI)** para preservar a transitividade relativizada ao tempo.
* **Matriz de Origem:** George Myro (1985), Andre Gallois (1998) — seção 4.6 do artigo.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar a Identidade Temporária a todos os casos leva a uma ontologia onde a identidade é instável — nada é permanentemente idêntico, o que inviabiliza a noção de persistência.
* **Comportamento em Falta:** Ignorar a Identidade Temporária leva a dificuldades em casos de fusão de objetos (ex: dois objetos que se fundem em um só).
* **Força Oposta (Antítese):** A **Identidade Necessária** (Kripke) — a tese de que se a = b é verdadeiro, então é necessariamente verdadeiro em todos os tempos.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade Temporária levanta a pergunta: um `KnowledgeObject` pode se fundir com outro e se tornar um só? O Noösphera, seguindo a Lei II (Invariância da Identidade), **não adota** a Identidade Temporária como regra geral — a identidade é preservada ao longo do tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - No Noösphera, a identidade de um `KnowledgeObject` é **permanente** (o `id` não muda).
  - A Identidade Temporária seria aplicável apenas em casos extremos de fusão (ex: dois KOs se fundem em um só), onde um novo `id` seria criado.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a Lei II rejeita a Identidade Temporária como regra geral — a identidade não é temporária, é invariante.
  - **Lei X (Reconstruibilidade Histórica):** se a Identidade Temporária fosse adotada, a reconstruibilidade histórica seria comprometida, pois a identidade mudaria ao longo do tempo.