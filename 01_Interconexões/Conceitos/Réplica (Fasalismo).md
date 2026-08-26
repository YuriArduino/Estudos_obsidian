---
tipo: conceito
tags_principais: [fasalismo, identidade, navio-de-teseu]
status: "sintetizado"
areas_conceituais: ["Metafísica", "Filosofia do Tempo"]
autores_associados: 
  - "[[Justin Mooney]]"
oposto_dialetico:
  - "[[Navio de Teseu]]"
  - "Original (Substância)"
implementado_em: 
  - "[[KnowledgeObject]]"
  - "[[Representation]]"
---

# Réplica (Fasalismo)

## 1. Definição e Matriz de Origem
* **Definição Teórica:** No contexto do **Fasalismo** (Mooney, seção 4.8 do artigo), a *réplica* é o status atribuído a um objeto reconstruído a partir das partes originais de outro, mas que **não é idêntico** ao original. No caso do Navio de Teseu, Mooney argumenta que Reassembly (o navio reconstruído a partir das tábuas originais) não é um candidato a ser idêntico ao navio original — ele é apenas uma **réplica**. Isso ocorre porque, segundo o Fasalismo, não há sortais de substância (apenas sortais de fase), e a identidade é preservada pela continuidade da fase, não pela continuidade material.
* **Matriz de Origem:** Justin Mooney (2025b, p. 160-161) — mencionado no artigo (seção 4.8).

## 2. Tensão e Dialética (Forças Opostas)
* **Comportamento em Excesso:** Tratar toda reconstrução material como réplica leva a uma ontologia onde a continuidade material é desvalorizada — o que é contra-intuitivo para quem acredita que a matéria define a identidade.
* **Comportamento em Falta:** Ignorar a distinção entre réplica e original leva a confundir objetos que são apenas materialmente semelhantes com objetos que têm continuidade histórica.
* **Força Oposta (Antítese):** A **Continuidade Material** — a tese de que a identidade é preservada pela continuidade da matéria (ex: Reassembly é o navio original).

## 3. Tradução para a Arquitetura do Noösphera
* **Papel no Grafo/Simbólico:** A Réplica é um conceito importante para o Noösphera: se um `KnowledgeObject` é recriado a partir de um backup ou de um `payload` antigo, ele é o *mesmo* objeto (id) ou uma **réplica** (novo id)? O Fasalismo de Mooney sugere que é uma réplica — a identidade não é recuperada pela reconstrução material.
* **Aplicação em Código / Estrutura de Dados:**
  - No Noösphera, um `KnowledgeObject` recriado a partir de um `payload` antigo **não** é o mesmo objeto — a menos que o `id` seja explicitamente preservado e a continuidade histórica seja mantida.
  - Se o `id` for alterado, o novo objeto é uma **réplica**, não o original.
* **Relação com as Leis:**
  - **Lei II:** a identidade é preservada apenas se a continuidade histórica (id e Observations) for mantida.
  - **Lei X:** a reconstruibilidade histórica registra a relação entre o original e a réplica (ex: `Observation` de que a réplica foi criada a partir do payload do original).