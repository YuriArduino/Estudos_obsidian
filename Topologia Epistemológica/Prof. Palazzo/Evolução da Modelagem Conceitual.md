---
type: video-note
media-link: http://youtube.com/watch?v=0f8I9YvciEw
autor: Prof. Palazzo
publicado-em: 2021-08-11
visto-em: 2026-08-12T14:41:00
area: Tecnologia da Informação
tags:
  - computacao
  - modelagem_conceitual
  - modelagem_de_sistemas
  - metodologia_de_modelagem
  - ontologia
  - dados
  - sistemas_de_informacao
  - semantica
---
![Evolução da Modelagem](http://youtube.com/watch?v=0f8I9YvciEw)
> [!INFO] Resumo
>  A palestra apresenta a trajetória da modelagem conceitual, desde os "tempos heróicos" nos anos 60, passando pelo surgimento dos modelos hierárquicos e relacionais, até a era atual das ontologias semânticas, destacando a importância da representação do significado (semântica) nos sistemas de informação.

> [!NOTE] Definição Central
> 
**Modelagem Conceitual:** É uma representação de um sistema ou domínio da realidade por meio de conceitos e relacionamentos, focada em capturar a semântica (significado) para permitir a compreensão humana, validação e inferência computacional.

> [!QUOTE] Citação Importante
> 
"Todo conhecimento sobre um domínio de aplicação deveria ser conectado em um único esquema conceitual." — _Referência ao artigo seminal de 1975_.

## 1. O Início: Tempos Heróicos e Modelos Hierárquicos

_O cenário inicial onde analistas tinham poucas ferramentas e precisavam traduzir a realidade manualmente para modelos rígidos._

- [02:22-03:35](https://www.youtube.com/watch?v=0f8I9YvciEw&t=142s) **O início nos anos 60:** a era dos fluxogramas manuais, bancos de dados hierárquicos e programação em Cobol.
- [05:04](https://www.youtube.com/watch?v=0f8I9YvciEw&t=305#t=05:04.84) **Esquema Conceitual**: um único esquema conceitual (ANSI).
- [06:42-08:18](https://www.youtube.com/watch?v=0f8I9YvciEw&t=402s) **O modelo hierárquico (ex: IMS/DB):** estrutura em árvore onde a navegação era explícita e qualquer mudança física exigia reprogramação das aplicações.

## 2. A Evolução: Modelo Relacional e Semântica

_A mudança de paradigma para a independência de dados e a busca por organizar a informação para evitar anomalias._

- [08:19-10:27](https://www.youtube.com/watch?v=0f8I9YvciEw&t=499s) **O surgimento do modelo relacional (Codd, 1970):** foco no "o que fazer" e não "como fazer" (SQL), trazendo independência física.
- [10:31-16:15](https://www.youtube.com/watch?v=0f8I9YvciEw&t=631s) **Normalização (Formas Normais):** o processo de remover redundâncias e garantir que o modelo reflita dependências funcionais, evitando anomalias de atualização.
- [17:28-18:41](https://www.youtube.com/watch?v=0f8I9YvciEw&t=1048s) **O modelo Entidade-Relacionamento (Peter Chen, 1976):** a formalização que permitiu uma representação visual clara e validável com os usuários do sistema.

## 3. Rumo ao Futuro: Objetos e Ontologias

_A necessidade de representar estruturas complexas e a evolução para modelos baseados em significado._

- [21:00-23:15](https://www.youtube.com/watch?v=0f8I9YvciEw&t=1260s) **Bancos de dados orientados a objetos:** surgiram para superar as limitações da primeira forma normal, permitindo representar mapas e imagens.
- [23:23-24:55](https://www.youtube.com/watch?v=0f8I9YvciEw&t=1403s) **O modelo UML:** uma tentativa de unificar a especificação de sistemas.
- [25:00-27:29](https://www.youtube.com/watch?v=0f8I9YvciEw&t=1500s) **Ontologias:** a fronteira atual onde o modelo de dados permite inferências lógicas sobre o domínio.

---

## 🎯 Principais Pontos (Takeaways)

- A evolução da modelagem busca sempre um maior equilíbrio entre o desempenho da máquina e a representação clara do conhecimento humano.
- O impotante é representar a [[Semântica]], o significado atribuído aos elementos de expecíficos de uma experiência.
- A normalização é fundamental para evitar erros de consistência (anomalias de atualização), mas pode "esconder" a semântica original do negócio.
- Ontologias são a evolução necessária para mundos interconectados e sistemas que precisam "entender" e realizar inferências sobre os objetos do domínio.

---

## 🔗 Conexões e Conceitos Relacionados

- [[Semântica|Semântica Computacional]]
- [[Modelagem de Dados]]
- [[Lógica|Lógica de Primeira Ordem]]
- [[Sistemas de Gerenciamento de Banco de Dados (SGBD)]]

---

## 📚 Referências Citadas no Vídeo

- Artigo de [[Peter Chen]] (1976) sobre o Modelo Entidade-Relacionamento.
- [[E.F. Codd]] e o artigo sobre o Modelo Relacional RM/T - 1979).
- Artigo de [[Giancarlo Guizzardi ]] (2019) sobre modelagem orientada a ontologias.
- Manifesto de Bancos de Dados Orientados a Objetos ([[Atkinson]] et al.).