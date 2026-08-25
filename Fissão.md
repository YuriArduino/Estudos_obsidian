---
tipo: conceito
tags_principais: [identidade, tempo, paradoxo]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica"]
autores_associados: 
  - "[[David Lewis]]"
  - "[[Andre Gallois]]"
  - "[[Theodore Sider]]"
oposto_dialetico:
  - "[[Fusão]]"
implementado_em: 
  - "[[Observation]]"
  - "[[KnowledgeObject]]"
---

# Fissão

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Um processo pelo qual uma entidade $a$ existente em um tempo $t_1$ dá origem a duas entidades $b$ e $c$ em um tempo $t_2$, cada uma com uma reivindicação putativa de ser idêntica a $a$. O artigo (seção 4.0) distingue entre dois tipos de fissão: **simétrica** (ex: divisão de uma ameba) e **assimétrica** (ex: Navio de Teseu).
* **Matriz de Origem:** Filosofia Analítica — discutida no contexto de identidade pessoal (divisão de pessoas) e identidade de objetos.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aceitar que $b$ e $c$ são ambos idênticos a $a$ viola a transitividade da identidade (pois $b \neq c$).
* **Comportamento em Falta:** Negar que qualquer um seja idêntico a $a$ parece ignorar a forte continuidade entre $a$ e seus "descendentes".
* **Força Oposta (Antítese):** A **Fusão** — dois objetos se fundem em um só.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Fissão é um problema para o Noösphera se um `KnowledgeObject` puder se "dividir" em dois ramos de evolução (ex: uma decisão que gera duas interpretações divergentes).
* **Aplicação em Código / Estrutura de Dados:**
  - O Noösphera pode lidar com fissão criando **dois novos `KnowledgeObject`**, cada um com uma nova `id` e uma `Observation` que registra a relação de origem (ex: `KO2` e `KO3` derivam de `KO1`).
  - A **Lei X (Reconstruibilidade Histórica)** preserva a genealogia.
* **Relação com as Leis:**
  - **Lei II:** a identidade não é preservada na fissão — $b$ e $c$ não são idênticos a $a$, nem entre si. Novas identidades são criadas.
  - **Lei X:** a fissão deve ser registrada como uma `Observation` que documenta a bifurcação histórica.