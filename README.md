# Sistema de Pedidos — Programação Orientada a Objetos em Python

Este projeto foi desenvolvido com o objetivo de praticar conceitos fundamentais de Programação Orientada a Objetos (POO) em Python, modelando um fluxo simples de atendimento: cliente faz um pedido, atendente registra, pagamento é realizado e o recibo é emitido.

O código simula um pequeno sistema de pedidos, utilizando classes, objetos, métodos e interação entre eles.

# Objetivo do Projeto

Criei este código para exercitar:

Criação e interação entre classes

Encapsulamento de atributos e comportamentos

Composição entre objetos

Simulação de um fluxo real de atendimento

Organização lógica das responsabilidades de cada entidade

# Estrutura das Classes
# Cliente

Representa o cliente que realiza pedidos e efetua o pagamento.

Métodos principais:

fazer_pedido()

realizar_pagamento()

# Item

Corresponde a cada produto incluído no pedido.

Atributos:

nome

preco

# Pedido

Armazena todos os itens pedidos, calcula o valor total e exibe o resumo.

Métodos principais:

adicionar_item()

calcular_total()

exibir_pedido()

# Atendente

Responsável por registrar o pedido e emitir o recibo.

Métodos principais:

registrar_pedido()

emitir_recibo()

# Funcionamento do Sistema

Crio os objetos principais: cliente, atendente, pedido e itens.

O cliente adiciona produtos ao pedido.

O pedido é exibido com o total calculado.

O cliente confirma o pedido.

O atendente registra o pedido.

O cliente realiza o pagamento.

O atendente emite o recibo final.

# Como executar

Basta rodar o arquivo com Python 3:

python3 sistema_pedidos.py

# Exemplo de Saída
--- Cliente realiza o pedido ---
Item Sanduíche adicionado ao pedido.
Item Suco adicionado ao pedido.

--- Exibir resumo do pedido ---
Resumo do Pedido:
- Sanduíche: R$15.00
- Suco: R$5.00
Total: R$20.00

--- Cliente confirma o pedido ---
João realizou um pedido.
Pedido registrado pelo atendente Carlos.

--- Cliente realiza o pagamento ---
João pagou R$20.00 pelo pedido.

--- Atendente emite o recibo ---
Recibo emitido.
Resumo do Pedido:
- Sanduíche: R$15.00
- Suco: R$5.00
Total: R$20.00

# Licença

Este projeto é livre para estudos, melhorias e adaptações.

