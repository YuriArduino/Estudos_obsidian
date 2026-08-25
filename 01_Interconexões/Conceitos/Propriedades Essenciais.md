---
tipo: conceito
tags_principais: [ontologia, identidade, aristoteles]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Teoria da Identidade"]
autores_associados: 
  - "[[Aristóteles]]"
oposto_dialetico:
  - "[[Propriedades Acidentais]]"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Propriedades Essenciais

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Propriedades que um objeto **não pode perder** sem deixar de ser *ele mesmo*. Definem a identidade do objeto e sua pertença a uma categoria. Se uma propriedade essencial é alterada, o objeto deixa de existir como tal e é substituído por outro. Exemplo: para Sócrates, "ser racional" e "ser animal" são essenciais.
* **Matriz de Origem:** Aristóteles (*Categorias*, *Metafísica*) — a distinção entre essência (οὐσία) e acidente (συμβεβηκός).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Definir muitas propriedades como essenciais torna o objeto rígido e imutável — qualquer alteração mínima o destruiria, inviabilizando evolução e versionamento.
* **Comportamento em Falta:** Definir poucas ou nenhuma propriedade essencial dissolve a identidade do objeto — ele se torna um amontoado de propriedades acidentais sem núcleo (nominalismo radical).
* **Força Oposta (Antítese):** As **Propriedades Acidentais** — que podem mudar sem comprometer a identidade.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** As Propriedades Essenciais são o que define a identidade de um `KnowledgeObject` e o que a **Lei II (Invariância da Identidade)** protege.
* **Aplicação em Código / Estrutura de Dados:**
  - **Essenciais no Noösphera:** `id`, `type` base (herança), relações fundantes (ex: `KO possui Representation`), e as Leis que regem o objeto.
  - Qualquer tentativa de modificar uma propriedade essencial deve ser bloqueada ou tratada como criação de um novo objeto.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** propriedades essenciais são invioláveis — a identidade da estrutura de significado depende delas.
  - **Lei IV (Coerência):** deve verificar se uma operação tenta modificar uma propriedade essencial. Se sim, bloqueia ou força uma bifurcação.