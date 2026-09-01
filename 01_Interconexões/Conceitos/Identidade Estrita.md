---
"type:": conceito
tags_principais:
  - identidade
  - chisholm
  - metafisica
status: sintetizado
areas_conceituais:
  - Metafísica
  - Lógica
autores_associados:
  - "[[Roderick Chisholm]]"
  - "[[Joseph Butler]]"
oposto_dialetico:
  - "[[Identidade Frouxa]]"
  - "[[Identidade Popular]]"
implementado_em:
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[KnowledgeObject]]"
---

# Identidade Estrita

## 1. Definição e Matriz de Origem
* **Definição Teórica:** O sentido **filosófico e rigoroso** de identidade, segundo o qual duas coisas só são idênticas se compartilham **todas as suas partes**. Isso significa que um objeto que perde ou ganha uma parte não pode ser estritamente idêntico a si mesmo ao longo do tempo. O artigo (seção 4.3) apresenta a distinção de Chisholm: um copo que perde sua alça não é estritamente idêntico ao copo anterior (com alça), embora possa ser frouxamente idêntico.
* **Matriz de Origem:** Bispo Joseph Butler (séc. XVIII), desenvolvido por Roderick Chisholm (1969, 1976) — mencionado no artigo (seção 4.3).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir identidade estrita para tudo leva a uma ontologia onde nada persiste — qualquer mudança de partes destrói a identidade.
* **Comportamento em Falta:** Ignorar a identidade estrita leva a uma ontologia onde a identidade é frouxa demais — objetos poderiam mudar completamente e ainda serem considerados os mesmos.
* **Força Oposta (Antítese):** A **[[Identidade Frouxa]]** — o sentido popular de identidade, onde a mudança de partes é permitida.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade Estrita é o que define o `KnowledgeObject` em sua essência — o `id` e o `type` são invariantes e não podem mudar.
* **Aplicação em Código / Estrutura de Dados:**
  - **Identidade Estrita no Noösphera:** `KnowledgeObject.id` e `KnowledgeObject.type` (ex: `Decision` nunca se torna `Observation`).
  - Mudanças no `payload` (matéria) são permitidas, mas mudanças no `type` (forma) violam a identidade estrita.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade estrita é o que a Lei II protege — a essência do objeto não pode mudar.
  - **Lei IV (Coerência):** a Lei IV valida se as mudanças acidentais não violam a identidade estrita.