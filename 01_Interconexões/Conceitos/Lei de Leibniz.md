---
tipo: conceito
tags_principais: [logica, identidade, validacao]
status: "sintetizado"
areas_conceituais: ["Lógica", "Metafísica"]
autores_associados: 
  - "[[Leibniz]]"
oposto_dialetico:
  - "Identidade dos Indiscerníveis"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[Lei IV — A Exclusividade Cognitiva das Competências]]"
  - "[[Teste de Admissão Ontológica]]"
---

# Lei de Leibniz

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Também conhecida como **Princípio da Indiscernibilidade dos Idênticos** — afirma que se duas coisas são numericamente idênticas (são a mesma coisa), então elas compartilham **todas** as suas propriedades. Formalmente:  

  $$∀x∀y[x=y → ∀F(Fx → Fy)]$$  

  Ou seja, não pode haver uma propriedade $F$ que $x$ possua e $y$ não possua, se $x$ e $y$ são a mesma coisa. Este princípio é **fundamental** para qualquer teoria da identidade.
* **Matriz de Origem:** Gottfried Wilhelm Leibniz (séc. XVII), formalizado na lógica moderna como um dos pilares da lógica de primeira ordem com igualdade.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Exigir que a Lei de Leibniz se aplique a **todas** as propriedades, incluindo propriedades temporais (ex: "estar quente agora") e modalidades (ex: "poderia não ter existido"), pode gerar paradoxos — como o **Problema dos Intrínsecos Temporários** (Lewis).
* **Comportamento em Falta:** Ignorar a Lei de Leibniz permite que um sistema trate duas referências como idênticas mesmo quando elas possuem propriedades diferentes, quebrando a **coerência lógica** — como um mesmo `KnowledgeObject` ter duas `Representations` com `payloads` incompatíveis.
* **Força Oposta (Antítese):** A **Identidade dos Indiscerníveis** (princípio inverso: se duas coisas têm todas as propriedades em comum, então são idênticas) — mais controversa, não adotada pelo Noösphera.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Lei de Leibniz é o **critério formal de coerência** para a identidade. Se dois `KnowledgeObject` são o mesmo (mesmo `id`), então toda propriedade de um deve ser compatível com o outro.
* **Aplicação em Código / Estrutura de Dados:**
  - **Lei II (Invariância da Identidade):** é uma instância direta da Lei de Leibniz: *"Nenhuma representação altera a identidade da estrutura que representa"*.
  - **Teste de Admissão Ontológica (#2):** deriva da Lei de Leibniz: uma entidade candidata não pode ter propriedades que contradigam seu continente ontológico.
* **Relação com as Leis:**
  - **Lei II:** aplicação direta ao domínio do conhecimento.
  - **Lei IV:** a exclusividade cognitiva respeita a Lei de Leibniz.
  - **Lei IX:** garante que a Ontologia é a fonte da identidade — a Arquitetura não pode criar propriedades que contradigam a identidade definida pela Ontologia.