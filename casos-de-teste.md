## Casos de teste

**Cenário 1: Login com usuário válido**

- **Steps:** realizar login com usuário válido.
- **Resultado esperado:** usuário é redirecionado para a página *Products*.

**Cenário 2: Login com usuário bloqueado**

- **Steps:** realizar login com usuário bloqueado (*locked_out_user*).
- **Resultado esperado:** exibição de mensagem de erro informando que o usuário foi bloqueado.

**Cenário 3: Adicionar produto ao carrinho**

- **Steps:** clicar no botão *Add to cart*.
- **Resultado esperado:** ao clicar no botão *Add to cart*, o produto deve ser adicionado ao carrinho.

**Cenário 4: Remover produto do carrinho**

- **Steps:** clicar no botão *Remove*.
- **Resultado esperado:** ao clicar no botão *Remove*, o produto deve ser removido do carrinho.

**Cenário 5: Visualizar produtos no carrinho**

- **Steps:** clicar no ícone do carrinho.
- **Resultado esperado:** ao clicar no ícone do carrinho, devem ser exibidos os produtos no carrinho.

**Cenário 6: Fazer checkout**

- **Steps:** clicar no botão *Checkout* e preencher os dados.
- **Resultado esperado:** conseguir preencher todos os dados necessários e clicar em *Continue* para prosseguir.

**Cenário 7: Finalizar compra**

- **Steps:** verificar a descrição da compra e finalizar.
- **Resultado esperado:** conseguir visualizar a descrição e os valores, e finalizar a compra recebendo uma mensagem de agradecimento.

**Cenário 8: Voltar para a página Products**

- **Steps:** após finalizar a compra, retornar para a página *Products*.
- **Resultado esperado:** após receber a mensagem de compra realizada, clicar no botão *Back home* e ser redirecionado para a *Home* com sucesso.

**Cenário 9: Concluir a compra sem nenhum produto no carrinho**

- **Steps:** sem possuir nenhum produto no carrinho, tentar finalizar a compra.
- **Resultado esperado:** exibir uma mensagem de erro informando que não é possível finalizar a compra, pois não há nenhum produto no carrinho.

**Cenário 10: Teste com usuário problemático (*problem_user*)**

- **Steps:** remover produto.
- **Resultado esperado:** ao clicar em remover, o produto deve ser removido do carrinho.

**Cenário 11: Adicionar produto ao carrinho com *problem_user***

- **Steps:** validar a ação de adicionar ao carrinho.
- **Resultado esperado:** produto adicionado corretamente.

**Cenário 12: Exibição de produtos com *problem_user***

- **Steps:** validar se os produtos são exibidos corretamente.
- **Resultado esperado:** nome, imagem e preço corretos.

**Cenário 13: Checkout com *problem_user***

- **Steps:** validar a finalização da compra.
- **Resultado esperado:** pedido concluído com sucesso.

**Cenário 14: Ordenar produtos com *problem_user***

- **Steps:** utilizar o filtro de ordenação de produtos.
- **Resultado esperado:** os produtos devem ser ordenados.

**Cenário 15: Filtrar/ordenar com *performance_glitch_user***

- **Steps:** utilizar o filtro de ordenação de produtos.
- **Resultado esperado:** os produtos devem ser ordenados.

**Cenário 16: Voltar para a tela Home com *performance_glitch_user***

- **Steps:** clicar no botão de voltar.
- **Resultado esperado:** ser redirecionado para a tela em alguns segundos.

**Cenário 17: Remover produto com *error_user***

- **Steps:** clicar no botão *Remove*.
- **Resultado esperado:** ao clicar no botão *Remove*, o produto deve ser removido do carrinho.

**Cenário 18: Adicionar produto com *error_user***

- **Steps:** clicar no botão *Add to cart*.
- **Resultado esperado:** ao clicar no botão *Add to cart*, o produto deve ser adicionado ao carrinho.

**Cenário 19: Fazer checkout com *error_user***

- **Steps:** clicar no botão *Checkout* e preencher os dados.
- **Resultado esperado:** conseguir preencher todos os dados necessários e clicar em *Continue* para prosseguir.

**Cenário 20: Finalizar compra com *error_user***

- **Steps:** verificar a descrição da compra e finalizar.
- **Resultado esperado:** conseguir visualizar a descrição e os valores, e finalizar a compra recebendo uma mensagem de agradecimento.

**Cenário 21: Alinhamento dos elementos com *visual_user***

- **Steps:** acessar a página de produtos.
- **Resultado esperado:** todos os elementos devem estar alinhados corretamente e sem sobreposição.

**Cenário 22: Responsividade com *visual_user***

- **Steps:** diminuir o tamanho da tela para validar a responsividade.
- **Resultado esperado:** o sistema deve se adaptar ao tamanho da tela.
