### Projeto: Análise Exploratória de Dados

##  Contexto: 

Você faz parte da equipe de dados de uma empresa de análise de mercado de games. Sua primeira tarefa é explorar um conjunto de dados sobre as vendas de videogames ao longo dos anos para extrair alguns insights iniciais. A equipe quer entender melhor as tendências do mercado.

##  O Desafio:

Usando a biblioteca Pandas em Python, você deve analisar um dataset fictício (Base de dados para Case 1: Games) que contém as seguintes colunas:
*   Nome: Nome do jogo.
*   Plataforma: Console onde o jogo foi lançado (ex: PS4, X360, Wii).
*   Ano: Ano de lançamento.
*   Genero: Gênero do jogo (ex: Action, Sports, Shooter).
*   Publisher: Empresa que publicou o jogo.
*   Vendas_Global: Vendas totais em milhões de unidades.

##  Sua Tarefa

###   Carregamento e Limpeza:
Carregue o arquivo vgsales.csv em um DataFrame do Pandas.
Verifique se existem valores faltantes na coluna Ano e remova as linhas correspondentes.

###   Análise Descritiva:
Qual é o gênero de jogo que mais vendeu globalmente? (Some as vendas de todos os jogos do mesmo gênero).
Qual plataforma (console) teve o maior número de jogos lançados?
Crie uma nova coluna chamada Decada que classifique cada jogo como sendo dos "Anos 90" (1990-1999), "Anos 2000" (2000-2009) ou "Anos 2010" (2010-2016).

###   Visualização de Dados:
Crie um gráfico de barras mostrando as vendas globais totais para os 5 gêneros mais vendidos.
Crie um gráfico de linhas que mostre o total de jogos lançados por ano.

##  Conclusão:

Dados os insights adquiridos ao longo do case é possível inferir que jogos de ação têm uma preferência maior pelo público e que há uma quantidade maior de jogos para PC, uma vez que é um dispositivo/console mais popular, multi-uso e adotado pelo público em geral. O ano que mais lançaram jogos foi 2017.