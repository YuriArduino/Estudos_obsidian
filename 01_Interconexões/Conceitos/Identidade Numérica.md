---
tipo: conceito
tags_principais: [identidade, logica]
status: "sintetizado"
areas_conceituais: ["Lógica", "Metafísica"]
autores_associados: 
  - "[[Leibniz]]"
  - "[[Aristóteles]]"
oposto_dialetico:
  - "Identidade Qualitativa"
implementado_em: 
  - "[[KnowledgeObject]]"
---

# Identidade Numérica

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Duas coisas são **numericamente idênticas** quando são a mesma coisa — ou seja, há apenas *um* objeto, e não dois. Exemplo: a "estrela da manhã" e a "estrela da tarde" são numericamente idênticas (ambas se referem a Vênus). A identidade numérica é a relação de **mesmidade** (self-sameness), não de semelhança.
* **Matriz de Origem:** Distinção clássica na filosofia da identidade (usada no artigo da SEP, seção 1). É a relação que obedece à **Lei de Leibniz**.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Tratar a identidade numérica como absoluta e independente da mudança leva à impossibilidade de lidar com a evolução — qualquer alteração seria uma violação da identidade.
* **Comportamento em Falta:** Ignorar a identidade numérica leva ao colapso da individualidade — tudo que é parecido seria o mesmo, e a identidade se dissolve.
* **Força Oposta (Antítese):** A **Identidade Qualitativa** — ser exatamente igual em propriedades, mas não ser a mesma coisa.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Identidade Numérica é o que define o `KnowledgeObject` como uma entidade única. O `id` do `KnowledgeObject` é a **âncora numérica** que permanece constante independentemente do `payload` (conteúdo).
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `KnowledgeObject` possui um `id` único que preserva a identidade numérica.
  - Duas `Representations` com o mesmo `payload` são qualitativamente idênticas, mas se tiverem `ids` diferentes, são numericamente distintas.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade numérica é o que a Lei II protege — nada pode alterá-la.
  - **Lei IV (Coerência):** a Lei IV valida se as propriedades do objeto são coerentes com sua identidade numérica.