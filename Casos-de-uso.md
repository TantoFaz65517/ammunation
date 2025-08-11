Casos de uso


#Caso de Uso 1: Cadastro de Usuario

- Ator Principal: Usuario (comprador ou vendedor)

- Objetivo: Criar uma conta para acessar o site.

- Fluxo Principal:

	1. O usuario acessa a pagina de cadastro.

	2. Preenche nome, e-mail, senha e, opcionalmente, dados 	de endereco.

	3. Confirma o cadastro.

	4. O sistema envia um e-mail de verificacao.

	5. O usuario confirma o e-mail e tem acesso ao site.

##Fluxos Alternativos:

	- 3A: O usuario informa e-mail ja cadastrado -> sistema exibe erro.

	- 4A: O e-mail de confirmacao nao chega -> opcao de reenviar.

#Caso de Uso 2: Publicar Anuncio

- Ator Principal: Vendedor

- Objetivo: Cadastrar um produto para venda.

- Fluxo Principal:

	1. O vendedor acessa sua conta.

	2. Clica em "Novo Anuncio".

	3. Preenche titulo, descricao, preco, categoria e 	fotos.

	4. Confirma o anuncio.

	5. O sistema publica o produto e ele fica visivel para 	compradores.

-Fluxos Alternativos:

	- 3A: Fotos nao carregam -> opcao de tentar novamente.

	- 4A: Campos obrigatorios nao preenchidos -> sistema 	alerta e impede o envio.

#Caso de Uso 3: Comprar Produto

- Ator Principal: Comprador

- Objetivo: Adquirir um produto anunciado.

- Fluxo Principal:

	1. O comprador acessa o site.

	2. Pesquisa ou navega ate o produto desejado.

	3. Clica em "Comprar".

	4. Informa endereco de entrega e forma de pagamento.

	5. Confirma a compra.

	6. O sistema registra o pedido e envia confirmacao ao 	comprador e ao vendedor.

- Fluxos Alternativos:

	- 4A: Forma de pagamento invalida -> sistema solicita 	novo metodo.

	- 5A: Estoque insuficiente -> sistema informa 	indisponibilidade

Caso de Uso 3: Comprar Produto

- Ator Principal: Comprador

- Objetivo: Adquirir um produto anunciado.

- Fluxo Principal:

	1. O comprador acessa o site.

	2. Pesquisa ou navega ate o produto desejado.

	3. Clica em "Comprar".

	4. Informa endereco de entrega e forma de pagamento.

	5. Confirma a compra.

	6. O sistema registra o pedido e envia confirmacao ao comprador e ao vendedor.

-Fluxos Alternativos:

	- 4A: Forma de pagamento invalida -> sistema solicita 	novo metodo.

	- 5A: Estoque insuficiente -> sistema informa 	indisponibilidade.