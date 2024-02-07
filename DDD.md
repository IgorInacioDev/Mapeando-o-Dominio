### Entidades ###
#Produto
#Fornecedor
#Cliente
#Venda
#Compra


### Casos de Uso ###
#Venda - Criação de uma ordem de venda, tendo que diminuir a quantidade de produtos do estoque de acordo com o produto e quantidade da ordem de venda. Tem que ser cadastrado no banco de dados(Estoque) para consulta da ordem. tendo que conter, valor de venda, produto, forma de pagamento, quantidade, e informações do comprador para possibilitar a criação de métricas do sistema.

#Compra - Criação e Gerenciamento da ordem de compra. Podendo ser feita automaticamente com base nas quantidades minimas de estoque e nas tendencias de vendas. Caso possivel integrar o sistema com os fornecedores para ter acesso automaticamente sobre os prazos de entrega.

#Retirada do produto - Possibilidade de excluir o cadastro de um produto. (Sem retirar os historicos e métricas daquele produto)

#Cadastro de produto - Nome, UUID, custo, valor de venda e informações extras/opcionais.(ex: Cor, Tamanho)

#Rastreamento de produto individualmente - Identificação de Item individualmente via UUID

#Definição de quantidade minima para estoque - Definir quantidade minima do estoque de um unico produto.

#Alerta de falta de estoque - Lançar um aviso caso o produto estiver perto de chegar ao limite de estoque minimo (Via e-mail e Aviso no gerenciamento de Estoque)

#Consulta de Historico e Métricas - Consultar as vendas feitas, e o fluxo de saida e entradas de produtos do estoque.(Orgaização com métricas e datas. possibilitando a consulta e apresentação de métricas por determinado produto,  lucro ou vendas, sendo possivel ver comparativos com outros produtos e ver as tendencias de quais produtos tem mais movimentação, lucro ou venda por um determinado periodo de tempo ou historico completo.  )

#Rastreamento via informações extras - Consultar um ou mais produtos por alguma informação extra, exemplo cor/Tamanho

#Gerenciamento de Ordem de venda - Capacidade de modificar , alterar ou excluir informações da ordem escolida.

#Gerenciamento de Ordem de compra - Capacidade de modificar, alterar ou excluir informações da ordem escolida.

#Gerenciamento de Prduto - Capacidade de modificar, alterar ou excluir as informações do produto.

#Consulta de vendas - Consultar uma venda utilizando UUID, cliente, produto, data e valor. Retornando informações da mesma.

#Consulta de Clientes - Consultar um Cliente, via UUID, nome ou informações de cadastro. Retornando compras, ticket medio, e produtos adquiridos.

#Consulta de Fornecedores - Consulta de pedidos de compras pendentes, enviados e finalizados. Retornando os pedido solicitados de acordo com o filtro.

#Consulta de compras - Consulta de Historico de Compras. Retornando produto, fornecedor, valor, e quantidade de produtos do pedido, e quantidade total.

