### Entidades ###
#Produto
#Fornecedor
#Cliente
#Venda
#Compra


### Casos de Uso ###
#Venda - Criação de uma ordem de venda, tendo que diminuir a quantidade de produtos do estoque conforme o produto e quantidade da ordem de venda. Tem que ser cadastrado no banco de dados(Estoque) para consulta da ordem. Tendo que conter, valor de venda, produto, forma de pagamento, quantidade, e informações do comprador para possibilitar a criação de métricas do sistema.

#Compra - Criação e Gerenciamento da ordem de compra. Podendo ser feita automaticamente com base nas quantidades mínimas de estoque e nas tendências de vendas. Caso possível integrar o sistema com os fornecedores para ter acesso automaticamente sobre os prazos de entrega.

#Retirada do produto - Possibilidade de excluir o cadastro de um produto. (Sem retirar os históricos e métricas daquele produto)

#Cadastro de produto - Nome, UUID, custo, valor de venda e informações extras/opcionais.(ex: Cor, Tamanho)

#Rastreamento de produto individualmente - Identificação de Item individualmente via UUID

#Definição de quantidade mínima para estoque - Definir quantidade mínima do estoque de um único produto.

#Alerta de falta de estoque - Lançar um aviso caso o produto estiver perto de chegar ao limite de estoque mínimo (Via e-mail e Aviso no gerenciamento de Estoque)

#Consulta de Histórico e Métricas - Consultar as vendas feitas, e o fluxo de saída e entradas de produtos do estoque.(Organização com métricas e datas. Possibilitando a consulta e apresentação de métricas por determinado produto, lucro ou vendas, sendo possível ver comparativos com outros produtos e ver as tendências de quais produtos tem mais movimentação, lucro ou venda por um determinado tempo ou histórico completo.  )

#Rastreamento via informações extras - Consultar um ou mais produtos por alguma informação extra, exemplo cor/Tamanho

#Gerenciamento de Ordem de venda - Capacidade de modificar, alterar ou excluir informações da ordem escolhida.

#Gerenciamento de Ordem de compra - Capacidade de modificar, alterar ou excluir informações da ordem escolhida.

#Gerenciamento de Produto - Capacidade de modificar, alterar ou excluir as informações do produto.

#Consulta de vendas - Consultar uma venda utilizando UUID, cliente, produto, data e valor. Retornando informações da mesma.

#Consulta de Clientes - Consultar um Cliente, via UUID, nome ou informações de cadastro. Retornando compras, ticket médio, e produtos adquiridos.

#Consulta de Fornecedores - Consulta de pedidos de compras pendentes, enviados e finalizados. Retornando os pedidos solicitados conforme o filtro.

#Consulta de compras - Consulta de Histórico de Compras. Retornando produto, fornecedor, valor, e quantidade de produtos do pedido, e quantidade total.
