---
"type:": conceito
tags_principais:
  - logica
  - propriedades
  - metafisica
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
autores_associados:
  - "[[Aristóteles]]"
  - "[[David Lewis]]"
oposto_dialetico:
  - "[[Predicação como relação binária]]"
implementado_em:
  - "[[Representation]]"
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
---

# Instanciação (Relação)

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Relação entre uma propriedade e seu portador (objeto). Tradicionalmente, a instanciação é uma relação binária: um objeto $o$ instancia uma propriedade $F$ ($Fo$). No entanto, o artigo (seção 2.4) propõe que, para resolver o Problema dos Intrínsecos Temporários, a instanciação poderia ser uma relação **triádica**: $o$ instancia $F$ em $t$ ($F(o, t)$). Isso permite que $o$ instancie propriedades diferentes em tempos diferentes sem contradição.
* **Matriz de Origem:** Aristóteles (predicação); formalizado na lógica moderna como a relação entre indivíduos e universais.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar os lugares da relação de instanciação leva a uma proliferação de relações — cada nova dimensão (tempo, modalidade, mundo) exigiria um novo lugar na relação.
* **Comportamento em Falta:** Reduzir a instanciação a uma relação binária leva a dificuldades em lidar com a mudança temporal — como $o$ pode instanciar propriedades incompatíveis em tempos diferentes?
* **Força Oposta (Antítese):** A **Predicação Binária** — a visão tradicional de que instanciação é uma relação de dois lugares (objeto, propriedade).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A instanciação triádica sugere que um `KnowledgeObject` instancia um `payload` (propriedade) em um determinado `timestamp` (tempo). Isso permite que o objeto tenha diferentes `payloads` em diferentes momentos sem perder sua identidade.
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Representation` pode ser vista como uma **instanciação temporal** do `KnowledgeObject`: o objeto instancia aquele `payload` naquele `timestamp`.
  - A relação triádica (`KO`, `payload`, `timestamp`) permite rastrear a evolução do objeto sem sobrescrever estados anteriores.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é preservada porque o objeto é o mesmo, apenas suas instanciações variam.
  - **Lei X (Reconstruibilidade Histórica):** a instanciação triádica permite reconstruir a história do objeto a partir de suas diferentes instanciações no tempo.