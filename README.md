# Cadastro de Produtos em Java

## Descrição

Projeto desenvolvido em Java para cadastro e exibição de informações de produtos, aplicando conceitos de Programação Orientada a Objetos.

O sistema utiliza diferentes construtores para criação dos produtos e um atributo estático para controlar a quantidade total de objetos cadastrados.

## Tecnologias

- Java

## Conceitos aplicados

- Programação Orientada a Objetos
- Classes e objetos
- Construtores
- Sobrecarga de construtores
- Atributos estáticos
- Métodos estáticos
- Encapsulamento
- Instanciamento de objetos

## Estrutura do projeto

- `Produto.java` — representa o produto e contém seus atributos, construtores e métodos.
- `Principal.java` — responsável pela criação dos produtos e execução do programa.

## Funcionamento

A classe `Produto` possui os atributos `nome`, `preco` e `quantidadeTotal`.

O atributo `quantidadeTotal` é estático e funciona como um contador compartilhado entre os objetos criados.

Foram implementados dois construtores: um construtor padrão e outro que recebe o nome e o preço do produto.

O método `exibirDados()` apresenta as informações individuais de cada produto, enquanto o método estático `exibirQuantidadeTotal()` apresenta a quantidade total de produtos cadastrados.

## Objetivo

Aplicar conceitos de Programação Orientada a Objetos em Java, especialmente construtores, sobrecarga, atributos estáticos e métodos estáticos.

## Documentação

A documentação completa da atividade está disponível no arquivo PDF deste repositório.
