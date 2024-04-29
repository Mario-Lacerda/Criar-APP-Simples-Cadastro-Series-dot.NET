

<h1 align="center">Criando um APP simples de cadastro de séries em .NET<br>Digital Innovation One</h1>

Bootcamp Decola Tech 2a edição da [Digital Innovation One](https://digitalinnovation.one/).

Aprenda como criar um algoritmo simples de cadastro de séries para praticar seus conhecimentos de orientação a objetos, o principal paradigma de programação utilizada no mercado. Nesse projeto você vai aprender: Como pensar orientado a objetos, como modelar o seu domínio, como utilizar recursos de coleção.

<h3> Tecnologias utilizadas</h3>

- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [.NET Core](https://dotnet.microsoft.com/download)

<!--License session-->
<h3> Licença</h3>

- Este projeto está sob a licença [MIT](./LICENSE).



# Cadastro de séries



Neste projeto foi criado um APP simples de cadastro de séries em .NET com o conceito de CRUD.

A classe EntidadeBase foi criada só para ter um Id para as classes que herdarem dela.

A classe Serie herda da classe EntidadeBase.

A classe SerieRepositorio implementa a interface IReposiotoio.

A interface IRepositorio determina os métodos de listagem, retornar o Id, inserir, excluir, atualizar e próximo Id garantindo, assim que as classes que a herdarem tenham esses métodos.

O programa principal monta o cadastro em série, usando o banco de dados em memória com o uso de lista da classse SerieRepositorio.



## CRUD

**C**reate / Criar

**R**ead / Ler

**U**pdate / Atualizar

**D**elete / Excluir

## Criando o console



dotnet new console -n Series

## Abrir o projeto



code Series/
