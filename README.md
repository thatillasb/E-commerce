# Esquema E-commerce

### Software usado: MySQL Workbench

### Componentes principais:
Produto/Cliente/Pedido/Pagamento/Estoque/Conta/Entrega
### Relacionamentos
Produto/cliente: Clientes selecinam e compram produtos.
Pedido/Cliente: Cada cliente pode realizar vários pedidos e cada pedido pertence a um cliente específico (Pessoa física ou jurídica).
Pedido/Produto: Um pedido pode conter vários produtos e cada produto pode pertencer a pedidos diferentes.
Produto/Fornecedor: Cada produto é fornecido por um ou mais fornecedores.
Produto/Estoque: O estoque pode conter vários produtos e um produto pode conter em mais de um estoque.
Pedido/Pagamento: Cada pedido está vinculado a uma transação de pagamento.
Pedido/Entrega do pedido: Cada peido tem um processo de entrega associado.
Cliente/Pagamento: Cada cliente pode efetuar mais de uma forma de pagamento.

### Fluxo do sistema:
1 - O cliente(Pessoa física ou jurídica) acessa a plataforma, navega pelos prosutos disponiveis e adciona os itens no carrinho.
2 - Após finalizar a compra, o sistema gera o pedido e aguarda a confirmação do pagamento.
3 - O estoque é atualizado automatiocamente para refletir a quantidade reduxida.
4 - O sistema processa o pedido, envia para o setor de logistica  e o despacha para o cliente com rastreamento.

## O esquema está disponível no formato de imagem abaixo:

![cenário E-commerce](https://github.com/user-attachments/assets/867cfe19-c327-4d2e-9cd8-d781859dc0d2)
