---
tipo: conceito
tags_principais: [ontologia, identidade, sortais]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia da Linguagem"]
autores_associados: 
  - "[[Aristóteles]]"
  - "[[Peter Geach]]"
  - "[[Justin Mooney]]"
oposto_dialetico:
  - "[[Sortais de Substância]]"
implementado_em: 
  - "[[Representation]]"
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Sortais de Fase

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Conceitos sortais que algo **pode perder** sem deixar de existir. Um sortal de fase descreve um estado transitório ou uma propriedade adquirida ao longo do tempo. Exemplos: "criança" (uma pessoa pode deixar de ser criança e continuar existindo), "estudante", "estátua" (se a estátua for considerada uma fase da argila). No artigo (seção 1 e 4.8), os sortais de fase são centrais para o **Fasalismo** (Mooney) e para a distinção entre identidade estrita e frouxa.
* **Matriz de Origem:** Filosofia Analítica (P.F. Strawson, David Wiggins) com raízes em Aristóteles.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar sortais de fase leva a uma ontologia onde tudo é transitório — nada tem essência, e a identidade é frágil.
* **Comportamento em Falta:** Não reconhecer sortais de fase leva a uma ontologia onde tudo é substância — a mudança é impossível, e a evolução é bloqueada.
* **Força Oposta (Antítese):** Os **Sortais de Substância** — conceitos que algo não pode perder sem deixar de existir.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O `format` de uma `Representation` (ex: JSON, Protobuf) é um **sortal de fase** — o objeto pode mudar de formato sem perder sua identidade.
* **Aplicação em Código / Estrutura de Dados:**
  - Uma `Representation` pode mudar de formato (JSON → Protobuf) sem que o `KnowledgeObject` perca sua identidade.
  - O `payload` de uma `Representation` é uma **fase** do objeto — pode ser alterado, transformado, versionado.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a mudança de fase (sortal de fase) é permitida porque não viola a identidade da estrutura de significado.
  - **Lei IV (Coerência):** a Lei IV valida se a fase (payload) está em conformidade com a substância (tipo/leis) do objeto.