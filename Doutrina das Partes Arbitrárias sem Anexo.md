---
tipo: conceito
tags_principais: [mereologia, van-inwagen, partes]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Mereologia"]
autores_associados: 
  - "[[Peter van Inwagen]]"
oposto_dialetico:
  - "[[Mereologia Irrestrita]]"
  - "[[Composição Irrestrita]]"
implementado_em: 
  - "[[Representation]]"
  - "[[KnowledgeObject]]"
---

# Doutrina das Partes Arbitrárias sem Anexo

## 1. Definição e Matriz de Origem
* **Definição Teórica:** A tese, defendida por Peter van Inwagen (1981), segundo a qual **nem toda divisão conceitual de um objeto corresponde a uma parte que realmente existe**. Ou seja, não podemos assumir que qualquer "fatia" de um objeto (ex: o copo sem a alça) é uma parte real do objeto enquanto ainda está anexada ao todo. Van Inwagen rejeita a Doutrina das Partes Arbitrárias sem Anexo (*Doctrine of Arbitrary Undetached Parts*) para resolver o puzzle do copo (Cup e Tcup): Tcup (o copo sem alça) não existe como uma parte separada de Cup enquanto a alça ainda está anexada. O artigo (seção 4.4) apresenta a rejeição de van Inwagen como uma solução para o puzzle do copo.
* **Matriz de Origem:** Peter van Inwagen (1981) — mencionado no artigo (seção 4.4).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aceitar a Doutrina das Partes Arbitrárias leva a uma ontologia onde há infinitas partes em qualquer objeto — cada divisão conceitual corresponderia a uma parte real.
* **Comportamento em Falta (van Inwagen):** Rejeitar a doutrina pode ser contra-intuitivo — parece óbvio que um copo sem alça é uma parte do copo com alça.
* **Força Oposta (Antítese):** A **[[Mereologia Irrestrita]]** — qualquer coleção de objetos forma um todo, o que implica que qualquer divisão arbitrária é uma parte legítima.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Doutrina das Partes Arbitrárias sem Anexo alerta o Noösphera para não tratar qualquer subconjunto de `Representations` como uma entidade independente. Uma `Representation` pode ser uma parte "arbitrária" de um `KnowledgeObject` e, portanto, pode não existir como entidade separada enquanto estiver anexada ao `KO`.
* **Aplicação em Código / Estrutura de Dados:**
  - No Noösphera, uma `Representation` só existe como entidade separada se for explicitamente instanciada como uma `Representation` — não se assume que toda subdivisão do `payload` é uma parte real.
  - Isso evita inflação ontológica: nem toda "fatia" de um `KO` precisa ser modelada como uma entidade.
* **Relação com as Leis:**
  - **Lei II:** a identidade do `KO` não é afetada pela existência ou não de partes arbitrárias.
  - **Gramática:** a Gramática define quais partes (representações) são legítimas — não são todas as divisões conceituais.