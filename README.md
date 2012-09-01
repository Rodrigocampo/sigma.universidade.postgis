curso-postgis
=============

-------------
Bem-vindo
-------------

Este é o repositório do curso de PostGIS da GeoCursos. Através deste site trocaremos exemplos de código, delegaremos exercícios
aos alunos e receberemos respostas dos mesmos.

O GitHub é "a rede social nerd", feita para compartilhar código e ajudar desenvolvedores a... desenvolver.

Aproveite, é uma grande ferramenta.

-------------
Estrututa
-------------

Temos que ter um pouco de estrutura.

Na wiki estarão diversas referências a coisas legais e importantes durante o curso. Uma delas é a lista de links, download,
requisitos, etc. Uma cópia da apresentação utilizada também estará na wiki para visualização online, no formato rst (reStructuredText);

No controle de código, teremos todos os exemplos do curso, em formato sql, para fácil visualização e testes.

Ocasionalmente teremos na wiki parte do código, parecido com isto:

```sql
CREATE TABLE public.ponto_interesse (
id SERIAL PRIMARY KEY,
nome varchar(64) UNIQUE
);

-- adicionar coluna geométrica
SELECT AddGeometryColumn('public','ponto_interesse','geometria',4674,'POINT',2);
-- SELECT AddGeometryColumn('public','ponto_interesse','geometria',4674,'POINT',3);
```

A idéia principal é que este código, quando seja apenas de um teste ad-hoc, esteja junto com outros em um único arquivo .sql.

Caso seja um exercício maior, ele estará em seu próprio arquivo .sql. De toda forma, a idéia é que ele esteja na wiki e no
controle de código.

-------------
Dúvidas
-------------

Mande-as para: georger.silva@gmail.com

-------------
Índice
-------------

### [Pré-requisitos](wiki/pre-requisitos.md)
### [Links importantes](wiki/links-importantes.md)
### [Instrutor](wiki/instrutor.md)
### [Cronograma](wiki/cronograma.md)
### [Ementa](wiki/ementa.md);
### [Aula 01](wiki/aula01.md);
### [Aula 02](wiki/aula02.md);
### [Aula 03](wiki/aula03.md);
### [Aula 04](wiki/aula04.md);
