# 📚 Casos de Uso – Plataforma de Compra, Venda e Troca de Itens

Este documento descreve os principais casos de uso do sistema, detalhando atores, objetivos, fluxos principais e de excessao.

---

## Caso de Uso 1: Cadastro de Usuário

**Ator Principal:** Usuário (comprador ou vendedor)  
**Objetivo:** Criar uma conta para acessar a plataforma.

**pre-condicoes:**
- O usuario nao deve ter cadastro previo com o mesmo email.
- O sistema deve estar online e acessivel.

**Fluxo Principal:**
1. O usuário acessa a página de cadastro.
2. Preenche nome, e-mail, senha e, opcionalmente, dados de endereço.
3. Confirma o cadastro.
4. O sistema envia um e-mail de verificação.
5. O usuário confirma o e-mail e passa a ter acesso à plataforma.

**Fluxos de excessao:**
- **3A:** O usuário informa um e-mail já cadastrado → sistema exibe mensagem de erro.
- **4A:** O e-mail de confirmação não chega → opção de reenviar.

**pos-condicoes:**
- conta criada com sucesso e registrada no sistema.
- Usuario autenticado e apto a realizar acoes na plataforma.

---

## Caso de Uso 2: Publicar Anúncio

**Ator Principal:** Vendedor  
**Objetivo:** Cadastrar um produto para venda ou troca.

**Pre-condicoes:**

- O vendedor deve ter uma conta ativa e autenticada.

- O sistema deve permitir publicações (não estar em manutenção).

**Fluxo Principal:**
1. O vendedor acessa sua conta.
2. Clica em "Novo Anúncio".
3. Preenche título, descrição, preço, categoria e fotos.
4. Confirma o anúncio.
5. O sistema publica o produto e ele fica visível para compradores.

**Fluxos de excessao:**
- **3A:** Fotos não carregam → opção de tentar novamente.
- **4A:** Campos obrigatórios não preenchidos → sistema alerta e impede o envio.

**Pos-condicoes:**

- Anuncio visivel na plataforma e disponivel para buscas.

- Dados do produto registrados no banco de dados.
---

## Caso de Uso 3: Comprar Produto

**Ator Principal:** Comprador  
**Objetivo:** Adquirir um produto anunciado.

**Pre-condicoes:**
- O comprador deve ter conta ativa e estar autenticado.

- O produto deve estar disponível em estoque.

**Fluxo Principal:**
1. O comprador acessa o site.
2. Pesquisa ou navega até o produto desejado.
3. Clica em "Comprar".
4. Informa endereço de entrega e forma de pagamento.
5. Confirma a compra.
6. O sistema registra o pedido e envia confirmação ao comprador e ao vendedor.

**Fluxos de excessao:**
- **4A:** Forma de pagamento inválida → sistema solicita novo método.
- **5A:** Estoque insuficiente → sistema informa indisponibilidade.

**Pos-condicoes:**
- Pedido registrado e aguardando processamento de pagamento e envio.

- Notificações enviadas para comprador e vendedor.
---