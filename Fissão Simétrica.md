---
tipo: conceito
tags_principais: [identidade, tempo, paradoxo]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica"]
autores_associados: 
  - "[[David Lewis]]"
  - "[[Theodore Sider]]"
oposto_dialetico:
  - "[[Fissão Assimétrica]]"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[Lei X — A Reconstruibilidade Histórica]]"
---

# Fissão Simétrica

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Um caso de fissão onde $b$ e $c$ estão relacionados a $a$ pela **mesma** relação. Exemplo clássico: uma ameba que se divide em duas — ambas as amebas filhas têm a mesma reivindicação de ser a ameba original, pois ambas continuam a mesma trajetória biológica. O artigo (seção 4.0) menciona a divisão amebica e a divisão hemisférica (no contexto da identidade pessoal) como exemplos de fissão simétrica.
* **Matriz de Origem:** Filosofia Analítica — discutida no contexto de identidade pessoal (divisão do cérebro em dois hemisférios) e biologia (divisão celular).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Dizer que $b$ e $c$ são ambos idênticos a $a$ viola a transitividade (pois $b \neq c$).
* **Comportamento em Falta:** Dizer que nem $b$ nem $c$ são idênticos a $a$ parece ignorar a forte continuidade causal e material.
* **Força Oposta (Antítese):** A **Fissão Assimétrica** — onde $b$ e $c$ estão relacionados a $a$ por relações *diferentes* (ex: Navio de Teseu).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Fissão Simétrica é análoga a uma situação onde um `KnowledgeObject` é duplicado de forma idêntica (ex: cópia exata de um `payload` em dois `ids` diferentes). Ambas as cópias têm a mesma reivindicação de serem o original.
* **Aplicação em Código / Estrutura de Dados:**
  - O Noösphera resolve a fissão simétrica criando **dois novos objetos** com `ids` distintos, mas registrando a relação de origem na `Observation`.
  - A **Lei X (Reconstruibilidade Histórica)** documenta que ambos derivam do mesmo ancestral.
* **Relação com as Leis:**
  - **Lei II:** a identidade não é preservada — $b$ e $c$ não são idênticos a $a$, nem entre si.
  - **Lei X:** a história da fissão é registrada para que a genealogia seja preservada.