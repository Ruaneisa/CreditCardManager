# CreditCardManager - Gerenciador de Compras com Cartão de Crédito

O projeto CreditCardManager é uma aplicação Java que permite ao usuário registrar compras utilizando um cartão de crédito. O objetivo é criar uma classe para representar a compra (com descrição e valor), outra classe para representar o cartão de crédito (com limite, saldo e lista de compras) e uma classe principal com o método main para interagir com o usuário.

## Objetivos do Projeto

- Criar uma classe Compra para representar uma compra com atributos de descrição e valor.
- Criar uma classe CartaoCredito para representar um cartão de crédito com atributos de limite, saldo e lista de compras. Essa classe deve ter um método para registrar uma compra.
- Implementar uma classe Principal com o método main para interagir com o usuário:
  - Solicitar que o usuário informe o limite do cartão de crédito.
  - Criar um objeto CartaoCredito com o limite informado pelo usuário.
  - Solicitar que o usuário informe a descrição e o valor da compra.
  - Criar um objeto Compra com a descrição e valor informados pelo usuário.
  - Registrar a compra no cartão de crédito e imprimir na tela se ela foi realizada ou não, de acordo com o saldo remanescente.
  - Perguntar se o usuário deseja registrar uma nova compra ou finalizar.
  - Caso ele deseje continuar, repetir os passos de 3 a 6, caso não, imprimir na tela o saldo final do cartão e a lista de compras realizadas, ordenadas pelo valor.
