---
tipo: conceito
tags_principais: [superveniencia, lewis, metafisica]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia da Mente"]
autores_associados: 
  - "[[ (David Lewis]]"
oposto_dialetico:
  - "[[Reducionismo]]"
  - "[[Eliminativismo]]"
implementado_em: 
  - "[[Lei II — A Invariância da Identidade do Conhecimento]]"
  - "[[Observation]]"
---

# Princípio da Superveniência

## 1. Definição e Matriz de Origem
* **Definição Teórica:** O princípio segundo o qual **fatos de um certo tipo são determinados por fatos de um tipo mais básico**. Em metafísica, a superveniência é usada para descrever como propriedades de nível superior dependem de propriedades de nível inferior. No artigo (seção 4.5), David Lewis usa o princípio da superveniência para defender o **Quadridimensionalismo**: se todos os fatos básicos (instanciações de propriedades intrínsecas e relações externas) são os mesmos, então os fatos de nível superior (ex: a persistência de um objeto) também devem ser os mesmos. Isso apoia a visão de que um objeto é uma sequência de partes temporais.
* **Matriz de Origem:** David Lewis (1986, *On the Plurality of Worlds*) — mencionado no artigo (seção 4.5) como um argumento a favor do Quadridimensionalismo.

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Aplicar a superveniência de forma muito rígida leva ao **Reducionismo** — tudo é reduzido a fatos básicos, e propriedades de nível superior são apenas "epifenômenos" sem autonomia.
* **Comportamento em Falta:** Ignorar a superveniência leva ao **Eliminativismo** — propriedades de nível superior seriam completamente desconectadas da realidade básica, impossibilitando a explicação de como o mundo funciona.
* **Força Oposta (Antítese):** O **Reducionismo** (tudo é redutível a fatos básicos) e o **Eliminativismo** (propriedades de nível superior não existem).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** O Princípio da Superveniência fundamenta a ideia de que a identidade de um `KnowledgeObject` **supervém** sobre suas `Representations` e `Observations` — ou seja, a identidade é determinada pelos fatos básicos do sistema (payloads, timestamps, relações).
* **Aplicação em Código / Estrutura de Dados:**
  - A identidade de um `KO` (id) supervene sobre a totalidade de suas `Representations` e `Observations`.
  - Se duas instâncias do sistema têm os mesmos fatos básicos (mesmo histórico de `Representations` e `Observations`), então a identidade do `KO` é a mesma.
* **Relação com as Leis:**
  - **Lei II:** a identidade supervene sobre a história do objeto — a identidade é determinada pelos fatos básicos do sistema.
  - **Lei X:** a reconstruibilidade histórica exige que os fatos básicos (Observations) sejam preservados para que a superveniência possa ser verificada.