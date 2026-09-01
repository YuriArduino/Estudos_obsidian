---
"type:": conceito
tags_principais:
  - propriedades
  - metafisica
  - logica
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
autores_associados:
  - "[[David Lewis]]"
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Propriedades Extrínsecas]]"
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Propriedades Intrínsecas

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedades que um objeto possui independentemente de outros objetos ou de sua relação com o ambiente. Uma propriedade intrínseca não depende de nada externo ao objeto. Exemplos: "ser redondo", "ser feito de ouro", "ter massa". O artigo (seção 2.3) discute propriedades intrínsecas no contexto do **Problema dos Intrínsecos Temporários** de Lewis, onde ele argumenta que a mudança de propriedades intrínsecas (ex: ser redondo vs ser quadrado) é problemática para a identidade diacrônica.
* **Matriz de Origem:** David Lewis (1986), *On the Plurality of Worlds*; distinção clássica na metafísica analítica.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Tratar propriedades como intrínsecas quando são, na verdade, extrínsecas leva a uma ontologia onde o objeto é isolado e desconectado — ignorando que muitas propriedades dependem do contexto.
* **Comportamento em Falta:** Tratar propriedades intrínsecas como extrínsecas leva a uma ontologia onde tudo depende de tudo — o objeto perde sua identidade própria e se dissolve em relações.
* **Força Oposta (Antítese):** As **Propriedades Extrínsecas** — que dependem de outros objetos ou do ambiente.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** Propriedades Intrínsecas definem o que o `KnowledgeObject` *é* independentemente de suas relações. Exemplos: `id` (identidade), `type` (tipo essencial), e as Leis que o regem.
* **Aplicação em Código / Estrutura de Dados:**
  - **Intrínsecas no Noösphera:** `id`, `type` (ex: `Decision`, `Observation`), e as Leis que definem a essência do objeto.
  - Essas propriedades não podem ser alteradas sem comprometer a identidade do objeto.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** as propriedades intrínsecas são invioláveis — a identidade da estrutura de significado depende delas.
  - **Lei IV (Coerência):** a Lei IV deve garantir que as propriedades intrínsecas sejam coerentes com o tipo e as leis do objeto.