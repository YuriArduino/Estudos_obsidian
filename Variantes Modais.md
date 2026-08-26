---
tipo: conceito
tags_principais: [modalidade, plenitude, coincidencia]
status: "sintetizado"
areas_conceituais: ["Lógica Modal", "Metafísica"]
autores_associados: 
  - "[[Maegan Fairchild]]"
  - "[[Penelope Mackie]]"
oposto_dialetico:
  - "[[Objeto Único]]" 
  - "(Sem Variantes)"
implementado_em: 
  - "[[Representation]]"
  - "[[KnowledgeObject]]"
---

# Variantes Modais

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Objetos que coincidem no espaço-tempo com outro objeto, mas diferem em quais propriedades são **essenciais** vs **acidentais**. No artigo (seção 4.7), o exemplo da igreja é usado: um prédio pode ser simultaneamente um *lugar de culto*, uma *igreja* (com elementos religiosos), e um *estúdio de arte* — cada um é uma variante modal do mesmo substrato, diferindo em quais propriedades são essenciais. A **Plenitude Modal** sustenta que todas essas variantes existem.
* **Matriz de Origem:** Maegan Fairchild (2019, 2020), Penelope Mackie (2008) — mencionado no artigo (seção 4.7).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar variantes modais leva a uma **inflação ontológica** — infinitos objetos para cada região do espaço-tempo.
* **Comportamento em Falta:** Ignorar variantes modais leva a uma ontologia onde a escolha de quais objetos existem parece arbitrária (antropocêntrica).
* **Força Oposta (Antítese):** A **Unicidade Modal** — a tese de que apenas um objeto existe em cada região, e suas propriedades modais são fixas.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** As Variantes Modais são análogas a diferentes `Representations` de um mesmo `KnowledgeObject` — cada uma pode destacar diferentes aspectos (essenciais ou acidentais) do objeto.
* **Aplicação em Código / Estrutura de Dados:**
  - Um `KnowledgeObject` pode ter múltiplas `Representations` (JSON, Protobuf), cada uma destacando propriedades diferentes (ex: uma pode destacar o `payload` essencial, outra o `payload` acidental).
  - O Noösphera gerencia essas variantes através da **Lei IV (Coerência)** — todas as `Representations` devem ser compatíveis com o tipo essencial do `KO`.
* **Relação com as Leis:**
  - **Lei IV:** a coerência garante que as variantes modais (Representations) não entrem em conflito.
  - **Lei II:** a identidade essencial do `KO` une todas as variantes.