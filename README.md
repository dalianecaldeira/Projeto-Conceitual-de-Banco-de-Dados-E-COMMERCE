O diagrama representa a estrutura de um sistema de e-commerce, organizando clientes, produtos, pedidos, pagamentos e entregas.
A entidade Cliente pode ser do tipo CPF (Pessoa Física) ou CNPJ (Pessoa Jurídica), separadas em tabelas específicas. Um cliente pode realizar vários Pedidos.
O Pedido registra informações como status, descrição e valor do frete, e está relacionado ao cliente que realizou a compra.
Os Produtos são cadastrados com descrição, categoria e valor. Um pedido pode conter vários produtos, e um produto pode estar presente em vários pedidos. Esse relacionamento é resolvido por uma tabela associativa que também armazena a quantidade comprada.
O sistema também controla:
Fornecedor, responsável por disponibilizar produtos.
Estoque, com controle de quantidade por produto.
Forma de Pagamento e Pagamento, permitindo registrar como e quando o pedido foi pago.
Entrega, que armazena status e código de rastreio vinculados ao pedido.
