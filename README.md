# finances-mono
Finances
## Estórias

1 - Conseguir registrar contas, poderemos registrar contas como conta corrente, conta investimento e conta cartão de crédito o sistema teria que ter a flexibilidade para adicionar novos tipos de contas.

2 - Conseguir inserir/editar/remover um registro que pode ser credito/despesa, ele terá os campos abaixo:
id do registro
id do usuário do registro
id do tipo de conta que foi registrado
id categoria do registro
Tipo do registro se é despesa ou crédito
valor do registro
data do registro do registro
descrição do registro
tags para relacionar registros
nota de registro

3 - Um registro pode ser configurado como registro fixo, caso isso ocorra será necessário colocar a periodicidade, data limite ou quantas vezes vai se repetir ou fixo por tempo indefinido.

4 - Caso você remova/edite um registro fixo você precisa ter a opção de remover/editar apenas aquele registro, remover/editar a partir daquele registro e remover/editar todos os registros

5 - Os registros precisam ser agrupados por tipo de conta, por mês corrente e por demais meses.

6 - Conta cartão de crédito precisa ter uma visão por fatura corrente

7 - Conta cartão de crédito precisa mostrar melhor dia de compra (quando vira a fatura)

8 - No dashboard o cartão precisa ter a opção de exibir por mês corrente ou fatura onde ser for por fatura deverá exibir se é a fatura atual ou na próxima fatura futura.

9 - Quando a fatura virar precisa gerar na conta corrente principal uma despesa com o valor total da fatura esse registro precisa ter um tipo especial

10 - Cada registro da conta corrente precisa ter uma efetivação ela pode ser configurada como manual ou automática

11 - Registro do tipo pagamento de fatura precisa ser sempre manual pois o usuário vai ter a opção de marcar que foi pago a fatura total ou parcial

12 - O usuário poderá marcar o pagamento da fatura deixando a data de efetivação para o futuro se quiser

13 - Todo o registro de despesa deverá ter um campo de juros que será opicional de colocar e juros/encargos deverá ser uma categoria (visão separada e consolidada)

14 - O sistema deverá ter uma visão do fluxo de caixa com filtro de contas respeitando a visão do cartão de crédito.

15 - Deverá ter uma tela de dashboard com o resumo de todas as contas

16 - Caso tenha mais de uma conta do mesmo tipo deverá ter a opção de mostrar a visão consolidade ou por conta.

17 - Cada conta deverá ter uma tela de extrato da conta.

18 - O sistema deverá ter um relatório de gastos por categória com um filtro por um intervalo de tempo sendo mes corrente, próximo mês e mês anterior como filtros pré definidos.

19 - O sistema deverá ter um relatório de gastos por tag com um filtro por um intervalo de tempo sendo mes corrente, próximo mês e mês anterior como filtros pré definidos.

20 - O sistema deverá ter um registro de orçamento por categoria ou tag

21 - No fluxo de caixa ou no extrato é necessário exibir o orçamento de cada categoria ou tag e caso passe do orçamento exibir a informação que determinada categoria passou o orçado.

22 - O sistema deverá ter um relatório de orçado vs realizado por categoria ou tag

23 - Registro de crédito/debito sem categoria vai ficar numa categoria fixa que é inesperado

24 - Cada conta deverá ser ligada a um usuário

25 - Ter a opção de logar/registrar um usuário

26 - O sistema deverá ter um outro tipo de registro que é o de dividas onde vai ter:
id da divida
instituição / pessoa dona da divida
tipo da divida se é cartão 
  1 - Dívidas Essenciais (Aluguel e Contas e Consumo)
  2 - Financiamentos (Bens Dados em Garantia)
  3 - Juros Altos (Cartão de Crédito, Cheque Especial e Empréstimo)
prioridade - ordem que vai ser paga
custo efetivo total da divida
prestações que faltam pagar ex: 3 de 12
valor da parcela
valor total em atraso
valor máximo na negociação
se está quitado ou não

27 - Um registro de divida deverá ter a opção de transferir o parcelamento para ser realizado em alguma conta

28 - Criar um registro de sonhos com:
investimentos associados ao sonho
nome do sonho
descriçao do sonho
valor do sonho

29 - Efetivado o pagamento com atraso deverá ser calculado os encargos como um registro manual dentro da conta.

30 - Efetivado um pagamento parcial de cartão de credito deverá ser calculo os encargos como um registro manual.

31 - Conta investimento poderá ter opção de por o tipo (renda fixa, renda variável)

32 - Conta investimento com registro renda fixa deverá ter a opção de por o rendimento e data de efetivação e calcular o rendimento automático e registrar mensalmente

33 - Conta investimento com registro de renda fixa precisa ter condições de resgate

34 - Conta investimento com registro de renda variável precisa ter registro do ativo sendo que ele irá exibir o rendimento por intervalo de 15 min, hora e dia

35- COnta investimento com registro de renda variável deverá aplicar todos os encargos e o valor do resgate do ativo além de das taxas

36 - Contas poderão ter opção de importar por csv e xlsx

37 - Contas poderão ter opção de importar ofx

38 - Contas poderão sincronizar com os registros do banco
