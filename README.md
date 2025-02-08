#  Criando um Dashboard de Vendas do Xbox

## Pergunta de Negócio 1 - Qual o faturamento Total de vendas de planos anuais (contendo todas as assinaturas agregadas).

## Pergunta de Negócio 2 - Qual o faturamento Total de vendas de planos anuais (separado por auto renovação ou que não é por auto renovação).

Construção de uma Tabela Dinâmica com a Planilha 'Bases'

Campos Utilizados:

1. Linhas: Auto Renewal.
2. Valores: Soma de Total Value.
3. Filtros: Subscription Type.

Resultado da Planilha de 'Cálculos': Gráfico com Rótulos de Linha 'No' e 'Yes' (Annual, Monthly, Quarterly).


## Pergunta Negócio 3 - Total de Vendas de Assinaturas do EA Play Season Pass

Construção de uma Tabela Dinâmica com a Planilha 'Bases'.

Campos Utilizados:

1. Linhas: Plan.
2. Valores: Soma de EA Play Season PassPrice.
3. Filtros: Subscription Type.

Resultado da Planilha de 'Cálculos': Big Number do Rótulo de Linha 'Ultimate' (Annual, Monthly, Quarterly) para EA Play Season Pass, porque os Rótulos de Linha 'Core' e 'Standard' são nulos.

## Pergunta Negócio 4 - Total de Vendas de Assinaturas do Minecraft Season Pass

Construção de uma Tabela Dinâmica com a Planilha 'Bases'.

Campos Utilizados:

1. Linhas: Plan.
2. Valores: Soma de Minecraft Season Pass Price.
3. Filtros: Subscription Type.
   
Resultado da Planilha de 'Cálculos': Big Number do Rótulo de Linha 'Ultimate' (Annual, Monthly, Quarterly) para Minecraft Season Pass, porque os Rótulos de Linha 'Core' e 'Standard' são nulos.


## Construção e Organização do Dashboard de Vendas do Xbox

Utilização das Paleta de Cores (em formato hexadecimal), logos e ícones da planilha 'Assets' e Utilização da Planilha 'Bases' para construção de Resultados da Planilha de 'Cálculos': Gráfico para "TOTAL SUBSCRIPTIONS XBOX GAME PASS" e de dois Big Numbers: "TOTAL SUBSCRIPTIONS EA PLAY SEASON PASS" e "TOTAL SUBSCRIPTIONS MINECRAFT SEASON PASS" resultando num Dashboard interativo.


 
