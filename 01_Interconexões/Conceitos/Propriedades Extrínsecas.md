---
"type:": conceito
tags_principais:
  - propriedades
  - relacoes
  - metafisica
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
autores_associados:
  - "[[David Lewis]]"
oposto_dialetico:
  - "[[Propriedades Intrínsecas]]"
implementado_em:
  - "[[Relation]]"
  - "[[04 — Gramática Formal]]"
---

# Propriedades Extrínsecas

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedades que um objeto possui em virtude de sua relação com outros objetos ou com o ambiente. Uma propriedade extrínseca depende de algo externo ao objeto. Exemplos: "ser casado com Sally" (depende de Sally existir), "ser mais alto que João" (depende da altura de João), "estar ao lado da mesa" (depende da posição da mesa). O artigo (seção 2.3) discute propriedades extrínsecas no contexto da distinção entre propriedades intrínsecas e extrínsecas, mencionando o exemplo de "ser da mesma altura que a Torre Eiffel".
* **Matriz de Origem:** David Lewis (1986), *On the Plurality of Worlds*.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Tratar propriedades como extrínsecas quando são, na verdade, intrínsecas leva a uma ontologia onde o objeto é completamente definido por suas relações — o que dissolve a individualidade.
* **Comportamento em Falta:** Ignorar propriedades extrínsecas leva a uma ontologia onde o objeto é isolado e desconectado — ignorando que muitas propriedades dependem do contexto.
* **Força Oposta (Antítese):** As **Propriedades Intrínsecas** — que o objeto possui independentemente de outros objetos.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** Propriedades Extrínsecas definem o que o `KnowledgeObject` *tem* ou *faz* em relação a outros objetos. Exemplos: `relações` (ex: `KO observa Observation`), `timestamp` (depende do tempo), e `formato` da representação (depende do contexto de uso).
* **Aplicação em Código / Estrutura de Dados:**
  - **Extrínsecas no Noösphera:** relações (ex: `KO relaciona-se com KO`), metadados (`timestamp`, `version`), e o `payload` da `Representation` (seu conteúdo depende do contexto de serialização).
  - Essas propriedades podem mudar sem comprometer a identidade do objeto.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade não é definida por propriedades extrínsecas — mudanças externas não violam a identidade.
  - **Gramática:** as relações (propriedades extrínsecas) são definidas pela Gramática, que especifica quais conexões são válidas.