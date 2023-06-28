# librasys
# Sistema de Biblioteca com Classe Scanner
Este é um simples sistema de biblioteca implementado em Java, utilizando a classe Scanner para entrada de dados do usuário. O sistema permite a realização de operações básicas de um CRUD (Create, Read, Update, Delete), permitindo o cadastro, consulta, atualização e exclusão de livros.

## Funcionalidades
 Cadastro de livros: o usuário pode inserir as informações do livro, como título, autor e ano de publicação.
 Consulta de livros: o usuário pode buscar livros pelo título ou autor e visualizar os resultados encontrados em formato de tabela.
 Atualização de livros: o usuário pode selecionar um livro existente e atualizar suas informações, como título, autor e ano de publicação.
 Exclusão de livros: o usuário pode remover um livro existente da biblioteca.

## Tecnologias utilizadas
 Linguagem de programação: Java
 Banco de dados: MySQL
 Classe Scanner: utilizada para a entrada de dados do usuário
 JDBC (Java Database Connectivity): utilizado para a conexão com o banco de dados MySQL

## Como usar
Clone o repositório para sua máquina local.
Certifique-se de ter o JDK (Java Development Kit) instalado em seu ambiente.
Configure o MySQL e crie um banco de dados chamado "biblioteca" com a tabela "livros" (consulte o script fornecido no arquivo librasys.sql).
Abra o projeto em uma IDE Java, como o IntelliJ IDEA ou Eclipse.
Configure as informações de conexão com o banco de dados.
Compile e execute o arquivo BibliotecaCRUD.java.
Siga as instruções apresentadas no console para interagir com o sistema.
