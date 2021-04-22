## Vendas

Nesta tela podemos realizar vendas para nossos clientes cadastrados, monitorar o estado de vendas feitas anteriormente e gerar relatórios.

### Realizando Venda

Para que uma venda seja realizada primeiramente devemos preencher os seguintes campos:
  - Tipo de Negociação (boleto, cartão, dinheiro). **\***
  - Cliente cadastrado **\***
  - Tipo de Movimentação **\***
  - Unidade
  - Unidade de Entrega
  - Observação
  - Voucher

Somente os campos marcados com * são necessários para a geração do rascunho.

Após completar os campos necessários, no menu principal da página clique em **`Salvar Rascunho`**

  <img src='/ui/assets/capturas-de-tela/botao-salvar-rascunho-vendas.png'/>
  

#### Adicionando itens à venda

Após salvar o rascunho de sua venda, clique em **`adicionar item`** no menu de opções secundário dentro da aba itens.
 <img src='/ui/assets/capturas-de-tela/adicionar-item.png'/>
 
 
<p align='center'>
  <img src='/ui/assets/capturas-de-tela/botao-adicionar-item-vendas.png'/>
<p>

Complete os campos relacionados ao item:
- Produto
- Local de estoque caso o item esteja estocado
- Quantidade
- Valor unitário
- Tipo de desconto

#### Adicionando desconto

- O desconto de uma venda é liberado de acordo com o perfil de desconto do vendedor que a está realizando.
- Este pode ser como um valor ou percentual.

#### Estados da venda

Após salvar o rascunho a venda estará com o status de *`Atendimento`*, até que seus itens sejam adicionados e seus dados confirmados.
Quando confirmada a venda constará como *`liberada`*.

O status de uma venda também informa se houve baixa financeira ou se seus itens já foram entregues ao consumidor final.

### Atenção

- Os valores de uma venda assim como o seu desconto não podem ser alterados após a sua liberação/confirmação. Estes dados podem ser modificados enquanto a venda for um rascunho.
- Para cancelar uma venda com o financeiro baixado, é necessário fazer o estorno de cada cobrança na aba `Financeiro` no ícone '*Estornar*'.

<p align='center'>
  <img src='/ui/assets/capturas-de-tela/botao-estornar-financeiro.png'/>
</p>
