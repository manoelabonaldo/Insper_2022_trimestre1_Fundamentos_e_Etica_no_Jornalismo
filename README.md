# Insper_2022_trimestre1_Fundamentos_e_Etica_no_Jornalismo
Projeto Final - Disciplina Fundamentos e Ética no Jornalismo de Dados - Insper 2022 
PROJETO FINAL

Possíveis investigações relacionadas à Arrecadação da Compensação Financeira pela Exploração Mineral – CFEM


Justificativa

A base de dados escolhida foi a que reúne dados sobre Arrecadação da Compensação Financeira pela Exploração Mineral – CFEM, fornecida pela Agência Nacional de Mineração - ANM, com detalhamento de Unidades Federativas e período (mês e ano).

Os dados são relevantes para o conhecimento do público em geral visto que a CFEM funciona como uma contrapartida paga aos municípios brasileiros que abrigam qualquer operação de mineração. É uma espécie de quantia paga como forma de reparar os impactos socioambientais desta atividade econômica e foi criada para que os municípios se estruturem e se diversifiquem economicamente visto que a atividade mineradora, e portanto a renda advinda dela, é algo finito. 

Dessa forma, é possível averiguar a quantia recebida mensal e anualmente por municípios que recebem a CFEM e, posteriormente, verificar se esse dinheiro está sendo empregado adequadamente. Pela Constituição, a CFEM deve financiar projetos que melhorem a vida da comunidade cuja atividade mineradora afeta, nas áreas de infraestrutura, qualidade ambiental, saúde e educação. 

Informações básicas

Arquivo: https://docs.google.com/spreadsheets/d/1gRQIRqEet8PMM3HJCTDop2qmCjoDIk7U/edit?usp=sharing&ouid=118196670240842803123&rtpof=true&sd=true 

Fonte: Agência Nacional de Mineração - ANM, autarquia vinculada do Ministério de Minas e Energia

Metodologia de coleta: Os dados coletados são referentes a receita bruta da venda do minério, no consumo do bem mineral ou da exportação, no valor de arrematação caso o bem mineral tenha sido adquirido em hasta pública ou sobre valor da primeira aquisição do bem mineral extraído de lavra garimpeira. 

Data de atualização: A base é atualizada diariamente pela ANM. As informações foram coletadas no dia 23/09/2022.

Limitações mais evidentes: Não há informação clara sobre como/onde fazer o download da base de dados. Precisamos transferir os dados manualmente da página da ANM para o Google Sheets a fim de poder analisar os dados com maior profundidade. Outra maneira seria fazer um pedido de LAI ou acessar os pedidos já realizados e verificar se algum arquivo referente ao tema já foi disponibilizado.


Roteiro de entrevista

Quais as cinco Unidades Federativas que mais arrecadaram CFEM e quanto cada um recebeu em 2022?

Somadas, quanto de dinheiro essas cinco Unidades Federativas receberam em 2022?

Quais os municípios que mais arrecadaram a CFEM e quanto cada um recebeu em 2022?

Somados, quanto de dinheiro esses cinco municípios receberam em 2022?

Quantos municípios receberam algum tipo de arrecadação referente a CFEM?

Qual estado com maior número de municípios que arrecadam CFEM, ou seja, que possuem algum tipo de atividade mineradora? Qual o estado com menor número de municípios que arrecadam CFEM?


Funções e cálculos (no Google Sheets)

Pergunta 1 
> Aba BR / UF
> Selecionar a primeira linha da tabela? 
> Criar filtro
> Classificar do maior para o menor (de Z a A no Google Sheets)

Resposta 1
As Unidades Federativas que mais arrecadaram CFEM em 2022 foram, respectivamente: Minas Gerais, Pará, Bahia, Goiás e Mato Grosso. 

Pergunta 2
> Aba BR / UF
> Selecionar Coluna Total
> Classificar do maior para o menor (de Z a A no Google Sheets)
=Soma (N2:N6)
Total: 

Resposta 2 
Somadas, as cinco Unidades da Federação receberam juntas, R$ 4.376.535.438,33, referentes à arrecadação da CFEM.

 
Pergunta 3 
> Aba Municípios BR
> Selecionar Coluna Total
> Classificar do maior para o menor (de Z a A no Google Sheets)

Resposta 3
Em 2022, os municípios que mais arrecadaram a CFEM foram, respectivamente, PARAUAPEBAS, no Pará ( R$922.065.300,50), CANAÃ DOS CARAJÁS, no Pará (R$ 723.337.952,21), CONCEIÇÃO DO MATO DENTRO, em Minas Gerais (R$ 263.877.021,37), Mariana, em Minas Gerais (R$ 221.034.624,44) e Itabirito, Minas Gerais ( R$218.051.011,89).


Pergunta 4
> Aba Municípios BR
> Selecionar Coluna Total
> Classificar do maior para o menor (de Z a A no Google Sheets)
> =Soma (O2:O6)

Resposta 4
Os cinco maiores municípios arrecadadores de CFEM receberam em 2022, somados, o valor de R$ 2.348.365.910,41.

Pergunta 5
> Seleciona a primeira linha e congela
> Seleciona a primeira coluna
> Clica com botão direito em "Estatísticas da coluna"
> Número de linhas = número de municípios

Resposta 5 
No Brasil, em 2022, 2589 municípios receberam alguma quantia referente a CFEM. 

Pergunta 6
> Aba Municípios BR
>Seleciona a coluna Estado
> Clica com botão direito em "Estatísticas da coluna"

Resposta 6

O estado com o maior número de municípios que em 2022 receberam algum valor referente a CFEM é Minas Gerais, que totaliza 499 municípios. 

Em contrapartida, o estado com menor número de municípios que arrecadaram CFEM em 2022 é o Acre, com apenas 3 municípios. 


Caminho para pauta

Os dados mais relevantes para uma reportagem sobre Compensação Financeira pela Exploração Mineral – CFEM é o ranking dos cinco municípios que mais arrecadaram em 2022. Deste modo, pode-se analisar, caso a caso, o perfil dos municípios: número de habitantes, índices socioeconômicos histórico da atividade mineradora, quais principais minérios são explorados, quais empresas desempenham a atividade na região, e se há indício de algum crime ambiental grave, como é o caso de Mariana, em Minas Gerais, que ocupa o quarto lugar entre os municípios brasileiros que mais arrecadaram a CFEM. 

Também é possível acessar os portais de transparência dos municípios e analisar como as prefeituras investiram os valores arrecadados. No início do ano, uma série de municípios passaram a ser investigados por suposto uso indevido de verbas da CFEM em shows de artistas sertanejos e de música pop, destino criticado por estudiosos do tema. Em uma investigação mais aprofundada, é possível identificar como cada prefeitura gasta esses valores e descobrir possíveis irregularidades. 
