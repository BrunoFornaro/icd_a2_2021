# A2 - Introdução à Ciência de Dados
## Análise exploratória de dados
Trabalho de A2 de Introdução à Ciência de Dados, primeiro semestre de 2021


## Integrantes do grupo
- Bruno Pereira Fornaro - B44398
- Gustavo Navarro Rozas - B42592
- Hugo de Araújo e Silva - B43907
- Matheus Medeiros Carvalho da Fonseca - B44252


## Obejtivos
Análise exploratória de dados, da [base de candidatos a vagas numa mineradora de ouro](https://www.kaggle.com/bryanb/applicants-for-a-gold-digger-position).


## Questões a serem exploradas
- Existe influência do gênero na contratação? 
- Existe influência da expectativa salarial com a contratação? 
- Uma pessoa com formação mais alta possui nota maior na prova? 
- Existe influência da idade na contratação? 
- Pessoas mais velhas tendem a ter uma formação mais completa? 
- Existe influência do curso do diploma na nota? E na contratação? 
- A disponibilidade é um fator importante para a contratação? 
- Pessoas mais velhas possuem mais experiência? 
- Pessoas com mais experiência possuem preferência na contratação?

Os nossos resultados estão no notebook ["a2_icd_2021.ipynb"](https://github.com/BrunoFornaro/icd_a2_2021/blob/main/a2_icd_2021.ipynb), assim como a base de dados está em "dados_candidatos.csv" (também pode ser vista no keggle no link em Objetivos).

## Conclusões
Utilizando os dados à nossa disposição na base de dados utilizada, fizemos uma análise exploratória dos dados orientada pelas perguntas iniciais que foram elaboradas, levando em consideração as variáveis da base de dados, o contexto e a natureza dos dados. A partir disso, geramos diversos gráficos, majoritariamente em análises bidimensionais.

É possível ver que o gráfico mais utilizado nas análises foi o gráfico de barras empilhadas, pois com eles conseguimos comparar melhor grande parte dos dados, já que a maioria das perguntas estavam relacionadas à contratação dos candidatos, sendo que eles são divididos em contratados e não contratados.

Apesar de respondermos todas as perguntas feitas inicialmente, os resultados que obtivemos não nos indicaram uma variável nessa base de dados que tenha grande influência na contratação (pelo menos não de forma isolada, das maneiras que pudemos analisar). Até mesmo a nota dos candidatos, que à primeira vista soa ser um fator determinante, não teve indicativos de ter forte influência na contratação, pois foram contratados funcionários com notas relativamente baixas, e numa proporção que não se alterou muito conforme a variação das notas. Em suma, a variável mostrou ter mais influência na contratação foi a experiência prévia dos candidatos, mas mesmo ela não apresentou uma forte correlação, além de que a amostra de candidatos com pouco tempo de experiência (4 anos ou menos) e com muitos anos de experiência (15 anos ou mais) é muito pequena com relação ao restante.

Com isso, nós nos estendemos um pouco além das perguntas para analisar os dados temporais, pois ainda não havíamos utilizado eles. O resultado nesse caso foi mais interessante, pois ao ver a expectativa salarial dos candidatos ao longo do tempo, era esperado que acontecesse um aumento da expectativa salarial (principalmente por uma inflação natural que os países sofrem), mas outra relação foi observada: a expectativa salarial média do tempo dividida pela formação dos candidatos nos mostrou que no geral a média da expectativa salarial dos candidatos é maior para aqueles com bacharelado e menor para os que possuíam doutorado. Porém, quando a base é filtrada para ser apresentada essa média apenas dos candidatos que foram contratados, essa relação não é mantida. Isto é, embora a expectativa salarial dos funcionários não aparenta influenciar na contratação anteriormente, pudemos ver que o perfil dos candidatos contratados é diferente do geral. Isso tudo pode indicar que exista um outro conjunto de fatores que esteja relacionado à escolha de funcionários que a empresa faz.


## Bibliografia
PANDAS - **Comparison with R / R libraries**. Disponível em: https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_r.html?highlight=comparison. Acessado em 17 de junho de 2021.

SEABORN - **seaborn.violinplot**. Disponível em: https://seaborn.pydata.org/generated/seaborn.violinplot.html. Acessado em 17 de junho de 2021.

STACKOVERFLOW - **How can I plot separate Pandas DataFrames as subplots?**. Disponível em: https://stackoverflow.com/questions/22483588/how-can-i-plot-separate-pandas-dataframes-as-subplots. Acessado em 17 de junho de 2021.

PANDAS - **pandas.DataFrame.plot.line**. Disponível em: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.line.html. Acessado em 17 de junho de 2021.

DELFTSTACK - **Pandas Remover Linhas com NaN**. Disponível em: https://www.delftstack.com/pt/howto/python-pandas/pandas-drop-rows-with-nan/. Acessado em 17 de junho de 2021.

SHANE - **Bar Plots in Python using Pandas DataFrames**. Disponível em: https://www.shanelynn.ie/bar-plots-in-python-using-pandas-dataframes/. Acessado em 17 de junho de 2021.

STACKOVERFLOW - **Pandas: bar plot xtick frequency**.https://stackoverflow.com/questions/19143857/pandas-bar-plot-xtick-frequency. . Acessado em 19 de junho de 2021.