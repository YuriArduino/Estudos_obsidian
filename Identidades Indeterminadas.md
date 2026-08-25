---
tipo: conceito
tags_principais: [identidade, logica, vagueza]
status: "sintetizado"
areas_conceituais: ["Lógica", "Metafísica"]
autores_associados: 
  - "[[Evans (Gareth)]]"
  - "[[Salmon (Nathan)]]"
oposto_dialetico:
  - "[[Identidade Determinada]]"
implementado_em: 
  - "[[Lei II]]"
  - "[[Lei IV]]"
---

# Identidades Indeterminadas

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A tese de que pode ser **indeterminado** (vago) se duas coisas são idênticas. Ou seja, uma sentença de identidade como `a = b` pode não ser nem verdadeira nem falsa — pode ser vaga ou indeterminada. O artigo (seção 3) discute identidades indeterminadas no contexto do argumento de Evans e Salmon, que tenta mostrar que essa noção é incoerente[reference:0].
* **Matriz de Origem:** Gareth Evans (1978), Nathan Salmon (1981) — o argumento de Evans-Salmon é uma *reductio* que visa mostrar que identidades indeterminadas são impossíveis[reference:1].

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aceitar identidades indeterminadas pode levar a uma ontologia onde a identidade é vaga e indefinida — o que inviabiliza a coerência do sistema.
* **Comportamento em Falta:** Rejeitar completamente a possibilidade de identidades indeterminadas pode ignorar casos onde a identidade é genuinamente vaga (ex: um clube que muda gradualmente de membros e regras).
* **Força Oposta (Antítese):** A **Identidade Determinada** — a tese de que toda sentença de identidade é ou verdadeira ou falsa (bivalência).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Noösphera **rejeita** identidades indeterminadas — seguindo o argumento de Evans-Salmon, a identidade deve ser sempre determinada. Dois `KnowledgeObject` ou são o mesmo (mesmo `id`) ou são distintos.
* **Aplicação em Código / Estrutura de Dados:**
  - A identidade no Noösphera é **binária**: `KO1 = KO2` é sempre verdadeiro ou falso.
  - A **Lei II (Invariância da Identidade)** garante que a identidade é determinada e invariante.
* **Relação com as Leis:**
  - **Lei II:** a identidade é determinada — não há "talvez" na identidade do `KnowledgeObject`.
  - **Lei IV:** a coerência é avaliada com base em uma identidade determinada — se `KO1 = KO2`, então suas propriedades devem ser compatíveis.