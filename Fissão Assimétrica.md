---
tipo: conceito
tags_principais: [identidade, tempo, paradoxo]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica"]
autores_associados: 
  - "[[Aristóteles]]"
  - "[[David Lewis]]"
  - "[[Roderick Chisholm]]"
oposto_dialetico:
  - "[[Fissão Simétrica]]"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Fissão Assimétrica

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Um caso de fissão onde $b$ e $c$ estão relacionados a $a$ por **relações diferentes**. Exemplo clássico: o **Navio de Teseu** — Replacement está relacionado ao original por continuidade da forma (mesmo design), enquanto Reassembly está relacionado ao original por continuidade material (mesmas tábuas). O artigo (seção 4.0) apresenta o Navio de Teseu como o exemplo paradigmático de fissão assimétrica.
* **Matriz de Origem:** Clássico da filosofia (Plutarco, Hobbes) — discutido na filosofia analítica contemporânea.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso (Replacement):** Priorizar a forma leva a dizer que Replacement é o original, mas ignora a continuidade material.
* **Comportamento em Falta (Reassembly):** Priorizar a matéria leva a dizer que Reassembly é o original, mas ignora a continuidade da forma.
* **Força Oposta (Antítese):** A **Fissão Simétrica** — onde ambos têm a mesma reivindicação.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Fissão Assimétrica é análoga a duas interpretações divergentes do mesmo `KnowledgeObject`: uma que preserva a forma (ex: o `type`) e outra que preserva o conteúdo (ex: o `payload`).
* **Aplicação em Código / Estrutura de Dados:**
  - O Noösphera resolve a fissão assimétrica priorizando a **identidade (`id`)** como o critério de continuidade — o objeto que mantém o `id` é o "original". Replacement e Reassembly são tratados como objetos distintos (novos `ids`), a menos que a continuidade histórica (Observations) determine o contrário.
  - A **Lei II (Invariância da Identidade)** garante que a identidade não é dividida — apenas um caminho pode ser o "original".
* **Relação com as Leis:**
  - **Lei II:** a identidade é preservada pelo `id` — Replacement ou Reassembly pode receber o `id` original, mas não ambos.
  - **Lei X:** a história é registrada para documentar a relação entre os dois caminhos.