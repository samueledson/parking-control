# API de Gerenciamento de Estacionamento (Parking Control API)

Este repositório contém o código-fonte de uma API de gerenciamento de vagas de estacionamento desenvolvida em Java com Spring Boot, Spring MVC, Spring Data JPA e Spring Validation. A API permite cadastrar, listar, atualizar e excluir vagas de estacionamento e também disponibiliza funcionalidades como paginação e validação de dados.

## Instalação

Para instalar a API, siga as instruções abaixo:

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o Java e o Maven instalados em sua máquina.
3. Execute o comando `mvn install` na pasta raiz do projeto para baixar as dependências e gerar o arquivo .jar.

## Como usar

Para executar a API, abra o terminal na pasta raiz do projeto e execute o comando `java -jar target/parking-control-0.0.1-SNAPSHOT.jar`. Em seguida, utilize um cliente HTTP para enviar requisições à API.

## Funcionalidades

A API disponibiliza as seguintes funcionalidades:

- Cadastro de vagas de estacionamento
- Listagem de vagas de estacionamento paginada
- Consulta de uma vaga de estacionamento específica
- Atualização de uma vaga de estacionamento existente
- Exclusão de uma vaga de estacionamento existente
