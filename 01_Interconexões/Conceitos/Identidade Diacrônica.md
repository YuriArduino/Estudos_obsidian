---
"type:": conceito
tags_principais:
  - identidade
  - tempo
  - persistencia
status: sintetizado
areas_conceituais:
  - Filosofia do Tempo
  - Metafísica
autores_associados:
  - "[[Aristóteles]]"
  - "[[David Lewis]]"
  - "[[Saul Kripke]]"
oposto_dialetico:
  - "[[Identidade Sincrônica]]"
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[Observation]]"
---

# Identidade Diacrônica

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Identidade que se mantém entre duas ocorrências de um objeto em **tempos diferentes**. Exemplo: "a mesa que está na sala agora é a mesma que você comprou no ano passado". A Identidade Diacrônica é o problema central do artigo da SEP — como algo pode ser o mesmo através da mudança?
* **Matriz de Origem:** Filosofia Ocidental (Aristóteles, Leibniz, Lewis, Kripke) — discutida na seção 2.1 do artigo.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir que a Identidade Diacrônica preserve **todas** as propriedades (inclusive temporais) leva ao paradoxo da mudança — nada poderia mudar sem perder a identidade.
* **Comportamento em Falta:** Ignorar a Identidade Diacrônica leva a uma ontologia onde o passado e o futuro são desconectados — o objeto de hoje não tem relação com o de ontem.
* **Força Oposta (Antítese):** A **Identidade Sincrônica** — identidade em um único instante.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade Diacrônica é o que garante que um `KnowledgeObject` permanece o mesmo através de suas múltiplas `Representations` e `Observations` ao longo do tempo.
* **Aplicação em Código / Estrutura de Dados:**
  - Um `KnowledgeObject` possui um `id` que persiste através do tempo, mesmo que seu `payload` mude.
  - As `Observations` registram a evolução do objeto, preservando sua continuidade histórica.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade diacrônica é o que a Lei II protege — o objeto deve permanecer reconhecível através do tempo.
  - **Lei X (Reconstruibilidade Histórica):** a identidade diacrônica exige que toda evolução seja registrada para que o histórico seja reconstruível.