---
tipo: conceito
tags_principais: [logica, tempo, propriedades]
status: "sintetizado"
areas_conceituais: ["Lógica", "Filosofia do Tempo", "Linguística"]
autores_associados: 
  - "[[Mark Johnston ]]"
  - "[[Sally Haslanger]]"
oposto_dialetico:
  - "[[Operador Sentencial]]"
  - "[[Visão Relacional]]"
implementado_em: 
  - "[[Representation]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Modificador Adverbial

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Uma das soluções para o Problema dos Intrínsecos Temporários (seção 2.4 do artigo). Segundo esta visão, 'em $t$' deve ser entendido como um modificador adverbial — ou seja, "Plate é redondo em $t_1$" significa que Plate tem redondeza *de modo em-t₁*. Isso permite que Plate tenha redondeza de um modo (em $t_1$) e quadratura de outro modo (em $t_2$), sem contradição. A ideia é que 'em $t$' modifica a *maneira* como a propriedade é instanciada, não a propriedade em si.
* **Matriz de Origem:** Mark Johnston (1987), Sally Haslanger (1989) — mencionados no artigo como defensores desta abordagem.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar modificadores adverbiais desnecessariamente leva a uma proliferação de modos de instanciação — cada tempo exigiria um modo diferente, tornando o sistema complexo.
* **Comportamento em Falta:** Ignorar modificadores adverbiais leva a dificuldades em explicar como algo pode ter propriedades incompatíveis em tempos diferentes.
* **Força Oposta (Antítese):** O **Operador Sentencial** — que trata 'em $t$' como um operador sobre proposições inteiras.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Modificador Adverbial sugere que cada `Representation` de um `KnowledgeObject` é uma *instanciação temporal* do objeto — o `payload` é a matéria instanciada de um modo específico (em um formato específico).
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Representation` pode ser vista como uma instanciação temporal do `KnowledgeObject` — o mesmo objeto se manifesta de modos diferentes em tempos diferentes (JSON em $t_1$, Protobuf em $t_2$).
  - A identidade é preservada porque o modo de instanciação não altera a essência do objeto.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é preservada independentemente do modo de instanciação.
  - **Lei IV (Coerência):** a coerência valida se cada modo de instanciação (cada `Representation`) é compatível com o tipo e as leis do objeto.