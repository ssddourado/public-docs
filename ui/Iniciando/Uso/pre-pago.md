# Sistema pré pago

Com esta funcionalidade é possível adicionar saldo à conta de suas unidades, debitar e definir um limite de vendas.

### Cadastrando uma unidade ao pré pago

Para cadastrar uma unidade ao sistema pré-pago basta acessar a página `Contrato do controle Pré-Pago` e preencher os seguintes dados:

- Unidade *
- Empresa *
- Valor Limite *
- Data Validade *
- Status *

### Movimentações em pré pago

A unidade começara com o saldo zerado e limite estipulado previamente. Após cada venda o saldo é somado ao valor da movimentação e é apresentado um total com saldo + limite.

- Para adicionar um valor ao saldo da unidade é preciso realizar uma venda com um tipo de movimentação que atualize o pré pago como receita.

- Para remover uma quantia do saldo basta realizar uma venda com um tipo de movimentação que atualize o pré pago como despesa.

Dependendo do tipo de movimentação configurado pelo usuário a venda poderá registrada na página de controle somente após a baixa no financeiro.

