---
tipo: conceito
tags_principais: [modalidade, lewis, mundos-possiveis]
status: "sintetizado"
areas_conceituais: ["Lógica Modal", "Metafísica"]
autores_associados: 
  - "[[David Lewis]]"
oposto_dialetico:
  - "[[Designadores Rígidos]]" 
  - "(Kripke)"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
---

# Teoria dos Correspondentes

## 1. Definição e Matriz de Origem
* **Definição Teórica:** Teoria desenvolvida por David Lewis para lidar com a **modalidade** (possibilidade, necessidade) sem recorrer a designadores rígidos. Segundo a Teoria dos Correspondentes (*Counterpart Theory*), um objeto em um mundo possível não é o mesmo objeto do mundo atual, mas apenas um **correspondente** (counterpart) — um objeto que se assemelha ao original de forma relevante. Isso permite que um objeto tenha propriedades diferentes em mundos possíveis sem violar a identidade. No artigo (seção 4.3 e 4.5), a Teoria dos Correspondentes é mencionada como uma ferramenta usada por Lewis e Sider para distinguir a estátua do lump de argila em termos de propriedades modais.
* **Matriz de Origem:** David Lewis (1986, *On the Plurality of Worlds*) — mencionado no artigo (seção 4.5).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Multiplicar correspondentes leva a uma inflação ontológica — cada objeto teria inúmeros correspondentes em diferentes mundos possíveis.
* **Comportamento em Falta:** Ignorar correspondentes leva a dificuldades em explicar como objetos podem ter propriedades modais diferentes sem violar a Lei de Leibniz.
* **Força Oposta (Antítese):** A teoria dos **Designadores Rígidos** (Kripke) — que afirma que o mesmo objeto pode existir em diferentes mundos possíveis, sem correspondentes.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Teoria dos Correspondentes sugere que diferentes `Representations` de um `KnowledgeObject` podem ser vistas como **correspondentes** umas das outras — elas não são idênticas, mas compartilham uma relação de continuidade (o `id` do `KO`). O `KO` é o "original" que une seus correspondentes (Representations).
* **Aplicação em Código / Estrutura de Dados:**
  - Cada `Representation` é um correspondente do `KnowledgeObject` em um determinado formato (JSON, Protobuf) e tempo (timestamp).
  - O `KO` une seus correspondentes sem ser idêntico a nenhum deles.
* **Relação com as Leis:**
  - **Lei II:** a identidade do `KO` é o "original" que une seus correspondentes.
  - **Lei IV:** a coerência valida se cada correspondente (Representation) é compatível com o original (tipo/leis do KO).