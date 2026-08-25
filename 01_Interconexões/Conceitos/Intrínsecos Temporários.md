---
tipo: conceito
tags_principais: [tempo, propriedades, lewis]
status: "sintetizado"
areas_conceituais: ["Filosofia do Tempo", "Metafísica", "Lógica"]
autores_associados: 
  - "[[David Lewis]]"
  - "[[Sally Haslanger]]"
  - "[[Mark Johnston]]"
oposto_dialetico:
  - "[[Propriedades Atemporais]]"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[Representation]]"
---

# Intrínsecos Temporários

## 1. Definição e Matriz de Origem
* **Definição Teórica:** O **Problema dos Intrínsecos Temporários** (formulado por David Lewis, seção 2.3 e 2.4 do artigo) é o problema de como algo pode ter propriedades intrínsecas incompatíveis em tempos diferentes. Exemplo: uma placa de metal (Plate) é redonda em $t_1$ e quadrada em $t_2$. O problema é: como Plate pode ter as propriedades intrínsecas "ser redondo" e "ser quadrado" sem contradição? Lewis propõe que a solução é o **Quadridimensionalismo**: Plate tem partes temporais — uma redonda em $t_1$ e uma quadrada em $t_2$.
* **Matriz de Origem:** David Lewis (1986), *On the Plurality of Worlds* — o problema é central para sua defesa do Quadridimensionalismo.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Tentar resolver o problema transformando propriedades intrínsecas em relacionais (Visão Relacional) leva à perda da noção de propriedade intrínseca — tudo se torna dependente do tempo.
* **Comportamento em Falta:** Ignorar o problema leva a uma ontologia onde a mudança é impossível — ou onde a identidade é quebrada pela mudança.
* **Força Oposta (Antítese):** A visão Tridimensionalista (Endurantismo) — objetos persistem como um todo, sem partes temporais, e a mudança é explicada de outra forma.

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Problema dos Intrínsecos Temporários é diretamente análogo ao problema que o Noösphera resolve: como um `KnowledgeObject` pode mudar de `payload` (propriedades intrínsecas do ponto de vista da representação) e ainda ser o *mesmo* objeto?
* **Aplicação em Código / Estrutura de Dados:**
  - A solução de Lewis (Quadridimensionalismo) é adotada pelo Noösphera: cada `Representation` é uma **parte temporal** do `KnowledgeObject`.
  - O `KnowledgeObject` não *muda* — ele tem diferentes `Representations` em diferentes tempos, cada uma com seu próprio `payload`.
  - A identidade é preservada porque o objeto é a soma de suas partes temporais.
* **Relação com as Leis:**
  - **Lei II (Invariância da Identidade):** a identidade é preservada através da continuidade das partes temporais.
  - **Lei X (Reconstruibilidade Histórica):** cada parte temporal (cada `Representation`) é registrada como uma `Observation`, permitindo reconstruir a história do objeto.
  - **Lei IV (Coerência):** a coerência é validada em cada parte temporal — cada `Representation` deve ser coerente com o tipo e as leis do objeto no momento em que foi instanciada.

## 4. Soluções para o Problema (Mapeamento)

O artigo (seção 2.4) lista várias soluções para o Problema dos Intrínsecos Temporários:

| Solução                           | Descrição                                                                | Status no Noösphera                                                 |
| :-------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------ |
| **Quadridimensionalismo (Lewis)** | Objeto tem partes temporais; cada parte tem propriedades diferentes.     | ✅ **Adotado** — cada `Representation` é uma parte temporal.         |
| **Visão Relacional**              | Propriedades intrínsecas são relações com o tempo.                       | ❌ Rejeitada — transforma intrínseco em extrínseco.                  |
| **Modificador Adverbial**         | Propriedades são instanciadas de modos diferentes em tempos diferentes.  | ⚠️ Útil como analogia, mas não adotado formalmente.                 |
| **Operador Sentencial**           | 'Em $t$' é um operador sobre proposições.                                | ⚠️ Útil para validar `Observations` no tempo.                       |
| **Instanciação Triádica**         | Instanciação é uma relação de três lugares (objeto, propriedade, tempo). | ⚠️ Útil para modelar `Representation` como instanciação temporal.   |
| **Presentismo**                   | Apenas o presente existe; o futuro não é real.                           | ❌ Rejeitado — o Noösphera preserva o histórico completo (Teoria B). |