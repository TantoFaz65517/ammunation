Casos de uso


#Caso de Uso 1 — Cadastro de Usuário

- Ator Principal: Usuário (comprador ou vendedor)

- Objetivo: Criar uma conta para acessar o site.

- Fluxo Principal:

	1. O usuário acessa a página de cadastro.

	2. Preenche nome, e-mail, senha e, opcionalmente, dados 	de endereço.

	3. Confirma o cadastro.

	4. O sistema envia um e-mail de verificação.

	5. O usuário confirma o e-mail e tem acesso ao site.

##Fluxos Alternativos:

	- 3A: O usuário informa e-mail já cadastrado → sistema 	exibe erro.

	- 4A: O e-mail de confirmação não chega → opção de 	reenviar.

#Caso de Uso 2 — Publicar Anúncio

- Ator Principal: Vendedor

- Objetivo: Cadastrar um produto para venda.

- Fluxo Principal:

	1. O vendedor acessa sua conta.

	2. Clica em "Novo Anúncio".

	3. Preenche título, descrição, preço, categoria e 	fotos.

	4. Confirma o anúncio.

	5. O sistema publica o produto e ele fica visível para 	compradores.

-Fluxos Alternativos:

	- 3A: Fotos não carregam → opção de tentar novamente.

	- 4A: Campos obrigatórios não preenchidos → sistema 	alerta e impede o envio.

#Caso de Uso 3 — Comprar Produto

- Ator Principal: Comprador

- Objetivo: Adquirir um produto anunciado.

- Fluxo Principal:

	1. O comprador acessa o site.

	2. Pesquisa ou navega até o produto desejado.

	3. Clica em "Comprar".

	4. Informa endereço de entrega e forma de pagamento.

	5. Confirma a compra.

	6. O sistema registra o pedido e envia confirmação ao 	comprador e ao vendedor.

- Fluxos Alternativos:

	- 4A: Forma de pagamento inválida → sistema solicita 	novo método.

	- 5A: Estoque insuficiente → sistema informa 	indisponibilidade

Caso de Uso 3 — Comprar Produto

- Ator Principal: Comprador

- Objetivo: Adquirir um produto anunciado.

- Fluxo Principal:

	1. O comprador acessa o site.

	2. Pesquisa ou navega até o produto desejado.

	3. Clica em "Comprar".

	4. Informa endereço de entrega e forma de pagamento.

	5. Confirma a compra.

	6. O sistema registra o pedido e envia confirmação ao 	comprador e ao vendedor.

-Fluxos Alternativos:

	- 4A: Forma de pagamento inválida → sistema solicita 	novo método.

	- 5A: Estoque insuficiente → sistema informa 	indisponibilidade.