# Modelagem de biblioteca para emprestimo de livros

## Regra de negocio / Requesitos

Uma biblioteca pretende controlar o empréstimo de livros, os dados
armazenados sobre cada biblioteca são, código, descrição e endereço,
uma biblioteca pode ter vários associados, e vários livros cadastrados,
uma mesma pessoa pode ser cadastrado em várias bibliotecas, no em
tando cada livro pode pertencer a uma biblioteca, empréstimos só serão
realizados para associados cadastrados, todo associado deve ter
matricula, nome e sexo. Os livros possuem ISBN e título. Em um dado
momento um livro só pode ser emprestado a um associado porém um
associado pode não pegar livros emprestados, mas também pode pegar
vários livros. Um livro pode ser escrito por vários autores e o mesmo
autor pode escrever vários livros, os dados dos autores, são, código e
nome. Um livro pode abordar muitos assuntos e um assunto pode ser
abordado por vários livros. Os dados de assunto são, código e
descrição.

## Modelo conceitual (DER 1.0)

![Diagrama ER](../../imagens/DER/Biblioteca_e_associado.PNG)

## Modelo conceitual (DER 1.1)

incluindo cardinalidades pertinentes a regra de negocio, atender os requisitos do sistema com o objetivo de atender o mundo real.

![Diagrama DER1.1](../../imagens/DER/biblioassoc2.PNG)

## Modelo conceitual (DER 1.2)

incluindo entidades associativas pertinentes a suas cardinalidades com o objetivo de atender os requisitos do sistema.

![Diagrama DER 1.2](../../imagens/DER/biblioassoc3.PNG)
[voltar](../../README.md)
