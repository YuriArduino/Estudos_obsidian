---
"type:": conceito
tags_principais:
  - mereologia
  - composicao
  - lewis
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
  - Matemática
autores_associados:
  - "[[David Lewis]]"
  - "[[Theodore Sider]]"
  - "[[Peter van Inwagen]]"
oposto_dialetico:
  - "[[Doutrina das Partes Arbitrárias sem Anexo]]"
  - "[[Nilismo Mereológico]]"
implementado_em:
  - "[[KnowledgeObject]]"
  - "[[Lei X — A Reconstruibilidade Histórica]]"
---

# Mereologia Irrestrita

## 1. Definição e Matriz de Origem
* **Definição Teórica:** O princípio segundo o qual **qualquer coleção de objetos forma uma soma mereológica** (um todo). Ou seja, não há restrições sobre quais objetos podem ser compostos em um todo — qualquer conjunto de objetos, por mais heterogêneo que seja, constitui um objeto adicional. Por exemplo, a soma da minha orelha com a Torre Eiffel existe como um objeto mereológico. O artigo (seção 4.3 e 4.5) menciona a mereologia irrestrita no contexto do Quadridimensionalismo de Lewis e do perspectivalismo de Sattig.
* **Matriz de Origem:** David Lewis (1986, *On the Plurality of Worlds*), Theodore Sider (2002) — associado ao Quadridimensionalismo e à composição mereológica irrestrita.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso (Composição Irrestrita):** Qualquer coleção de objetos forma um todo — leva a uma **inflação ontológica** extremamente indesejável, onde há infinitos objetos arbitrários (ex: a soma da minha orelha com a Torre Eiffel).
* **Comportamento em Falta (Nilismo Mereológico):** Não existem partes — apenas objetos simples (átomos) existem. Isso nega a noção de composição e inviabiliza estruturas complexas.
* **Força Oposta (Antítese):** A **[[Doutrina das Partes Arbitrárias sem Anexo]]** (van Inwagen) — que restringe quando partes podem ser consideradas reais.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Mereologia Irrestrita é um **alerta** para o Noösphera: se qualquer conjunto de `Representations` pudesse formar um `KnowledgeObject`, o sistema seria inundado por combinações arbitrárias de dados. Portanto, o Noösphera **não adota** a mereologia irrestrita.
* **Aplicação em Código / Estrutura de Dados:**
  - No Noösphera, um `KnowledgeObject` é composto por `Representations` **apenas quando há uma relação formal definida** (ex: `KO possui Representation`). Conjuntos arbitrários de `Representations` não formam um `KO`.
  - A **Gramática** define quais composições mereológicas são válidas — apenas relações autorizadas geram composição legítima.
* **Relação com as Leis:**
  - **Gramática:** a Gramática define quais relações de composição são válidas.
  - **Lei X (Reconstruibilidade Histórica):** a composição histórica é registrada por `Observations`, mas apenas para relações legítimas.