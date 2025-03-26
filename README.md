# mlg
Resolução da questão número 20, página 180, do livro do Gilberto A. Paula, disponível em: https://www.ime.usp.br/~giapaula/texto_2024.pdf

O objetivo é tentar explicar o custo médio de sinistros utilizando um modelo linear generalizado. O banco de dados consiste em 9 variáveis explicativas, referentes a uma amostra aleatória de 996 apólices de seguros de veículos referentes ao período 2004 - 2005. 
As variáveis do arquivo estão na seguinte ordem: (i) valorv (valor do veículo em 10000 dólares australianos), (ii) expos (exposição do veículo), (iii) nsinistros (número de sinistros no período), (iv) csinistros (custo total dos sinistros em dólares australianos), (v) tipov (tipo do veículo em 11 categorias), (vi) idadev (idade do veículo em 4 categorias), (vii) sexoc (sexo do condutor principal), (viii) areac (área de residência do condutor principal) e (ix) idadec (idade do condutor principal em 6 categorias).

Primeiramente foi aplicado um modelo linear generalizado apenas estimando o parâmetro do valor esperado, em seguida foi utilizado um modelo múltiplo, buscando estimar o parâmetro de dispersão para explicar a variância não constante (heterocedasticidade) dos resíduos do modelo.

Devido a natureza assimétrica e a existência de somente valores positivos, foi utilizado a distribuição gaussiana inversa. Será apresentado o modelo selecionado, e uma análise de diagnóstico.

