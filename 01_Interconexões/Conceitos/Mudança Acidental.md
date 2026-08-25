---
tipo: conceito
tags_principais:
  - ontologia
  - mudanca
  - aristoteles
status: sintetizado
areas_conceituais:
  - Metafísica
  - Filosofia da Natureza
autores_associados:
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Mudança Essencial]]"
implementado_em:
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
  - "[[Representation]]"
---

# Mudança Acidental

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Mudança que afeta propriedades não-essenciais de um objeto, sem comprometer sua identidade. O objeto permanece *o mesmo* após a mudança. Exemplos clássicos: uma casa ser pintada, cabelos ficarem grisalhos, um objeto mudar de posição.
* **Matriz de Origem:** Aristóteles (*Física*, *Metafísica*) — distinção entre mudança acidental e essencial como solução para o paradoxo da mudança.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Classificar toda mudança como acidental leva a uma ontologia onde a identidade é frágil e qualquer transformação é permitida — o objeto pode se tornar qualquer coisa sem perder sua identidade, o que dilui o conceito de identidade.
* **Comportamento em Falta:** Não reconhecer mudanças acidentais como legítimas leva a uma ontologia onde qualquer alteração destrói o objeto — o que inviabiliza a evolução e o versionamento.
* **Força Oposta (Antítese):** A **Mudança Essencial** — que altera a identidade do objeto e, portanto, implica sua destruição ou substituição.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Mudança Acidental é o fundamento ontológico para permitir que o `payload` de um `KnowledgeObject` mude sem que sua identidade seja comprometida.
* **Aplicação em Código / Estrutura de Dados:**
  - Alterar o conteúdo de uma `Representation` (ex: de JSON para Protobuf) é uma **mudança acidental** — a identidade do `KnowledgeObject` permanece.
  - Alterar metadados como `timestamp`, `version`, ou `cache` também são mudanças acidentais.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a mudança acidental é permitida porque não viola a identidade da estrutura de significado.
  - **Lei IV (Coerência):** deve validar se a mudança no `payload` ainda respeita o `type` e as leis do objeto — se a mudança for acidental, a Lei IV aprova; se for essencial, bloqueia.