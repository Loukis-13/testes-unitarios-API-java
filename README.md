## Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.

Neste projeto, foram desenvolvidos testes unitários para uma API REST para o gerenciamento de estoques de cerveja para o bootcamp da DIO.
Fora mostrado na live como desenvolver testes unitários para validar o sistema de gerenciamento de estoques de cerveja, os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito, e como desenvolver funcionalidades da nossa API através da prática do TDD.

Durante a sessão, foram abordados os seguintes tópicos:

* Baixar um projeto através do Git para desenvolver testes unitários. 
* Apresentação conceitual sobre testes: a pirâmide dos testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.
* Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
* Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest. 
* Desenvolvimento de testes unitários para validação de funcionalidades básicas: criação, listagem, consulta por nome e exclusão de cervejas.
* TDD: apresentação e exemplo prático em 2 funcionalidades importantes: incremento e decremento do número de cervejas no estoque.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suite de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

* Java 14 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
