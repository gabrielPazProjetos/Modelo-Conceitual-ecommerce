#  Modelo Conceitual – E-commerce

Este projeto apresenta um modelo conceitual de banco de dados para um sistema de E-commerce, com foco em representar as principais entidades e relacionamentos envolvidos em uma operação comercial online.

##  Objetivo

Refinar o modelo inicial com os seguintes requisitos:
- Diferenciar clientes Pessoa Física (PF) e Pessoa Jurídica (PJ)
- Permitir múltiplas formas de pagamento por cliente
- Controlar entregas com status e código de rastreio

##  Entidades principais

- Conta
- Cliente_PF
- Cliente_PJ
- Produto
- Pedido
- Item_Pedido
- Pagamento
- Entrega

##  Relacionamentos

- Uma conta pode ser PF ou PJ, nunca ambos
- Uma conta pode ter vários pagamentos e pedidos
- Um pedido pode ter vários itens
- Cada pedido possui uma entrega com status e rastreio

##  Diagrama

O diagrama conceitual foi criado com a ferramenta [diagrams.net](https://app.diagrams.net) e está disponível neste repositório no arquivo:
