---
"type:": conceito
tags_principais:
  - ontologia
  - mudanca
  - aristoteles
status: sintetizado
areas_conceituais:
  - Metafísica
  - Filosofia da Linguagem
autores_associados:
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Propriedades Essenciais]]"
implementado_em:
  - "[[Representation]]"
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Propriedades Acidentais

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedades que um objeto **pode perder ou trocar** sem que sua identidade seja afetada. São características contingentes que não definem *o que* a coisa é. Exemplos: ser alto, ser pintado de azul, estar em uma determinada posição, ter um determinado `timestamp` de criação.
* **Matriz de Origem:** Aristóteles (*Categorias*, *Metafísica*) — a distinção entre essência (οὐσία) e acidente (συμβεβηκός).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Classificar tudo como acidental dissolve a identidade — o objeto se torna um amontoado de propriedades contingentes sem núcleo estável (nominalismo radical).
* **Comportamento em Falta:** Não reconhecer propriedades acidentais como legítimas torna o objeto rígido e imutável — qualquer alteração seria uma mudança essencial, inviabilizando evolução e versionamento.
* **Força Oposta (Antítese):** As **Propriedades Essenciais** — que definem a identidade do objeto.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** As Propriedades Acidentais são o que permite que o `payload` de um `KnowledgeObject` mude livremente sem comprometer sua identidade.
* **Aplicação em Código / Estrutura de Dados:**
  - **Acidentais no Noösphera:** `Representation.payload` (conteúdo dinâmico), `timestamp` de criação, metadados de cache, `version` (se não for estrutural).
  - Essas propriedades podem ser alteradas, transformadas, versionadas sem que a identidade do `KnowledgeObject` seja afetada.
* **Relação com as Leis:**
  - **Lei IV (Coerência):** a Lei IV deve verificar se a mudança em uma propriedade acidental ainda respeita o `type` e as leis do objeto. Se a mudança for acidental, a Lei IV aprova.
  - **Lei II (Invariância da Identidade):** a mudança acidental é permitida porque não viola a identidade da estrutura de significado.