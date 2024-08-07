# trilhaDadosJR

Análise de Dados: Vendas de Cursos Online

Objetivos: realizar uma análise básica de dados utilizando Python, explorar um conjuto de dados pré-definidos para extrair insights simples através de estatísticas descritivas e visualizações gráficas.

Dataset: Base de dados fornecido pelo "Código Certo" para utilizar na "TrilhaDadosJR".

1- Bibliotecas usadas: pandas, matplotlib e seaborn.

2- Base de dados atribuído a variável "df". 

3- Utilizado ".dtypes" e ".shape" para saber os tipos de dados das variáveis e quantas linha e colunas tem.

4- Foi criado uma nova coluna com o total da venda de cada dia.

5- Foi usado o ".sum()" na coluna "total_receita" para mostrar a receita de todas as vendas.

6- Foi utilizado o ".groupby()" para agrupar a coluna "Nome do Curso" pela coluna "Quantidade de Vendas" e foi utilizado novamente o ".sum()" somar as vendas e foi utilizado o ".sort_values(ascending=False)" para colocar em ordem decrescente.

7- Para criar estatísticas descritivas utilizei o ".groupby()" com o método ".agg()" para retornar a soma, média, mínimo, máximo e desvio padrão das colunas "Quantidade de Vendas" e "total receita.

8- Mudei o estilo do gráfico com o "sns.set(style="whitegrid")" para uma melhor visualização.

9- Utilizei o "plt.rc" para aumentar o tamanho da imagem e o "plt.xticks" para colocar uma rotação nas datas para ficar legíveis.

10- Utilizei um "sns.lineplot()" para plotar um gráfico de linhas, "plt.savefig()" para salvar a imagem no computador local, "plt.legend" para colocar a caixa de legenda fora do gráfico e "plt.show()" para mostrar o gráfico.

11- Utilizei um "sns.barplot()" para plotar um gráfico de barras para poder fazer a comparação de aquisição de receita entre os cursos.


CONCLUSÕES:

- Com os dados extraídos com essa analise, podemos afirmar que a receita total gerada pela venda de todos os cursos é de R$32735.10 reais.
- O curso "Introdução à Programação em Python" é o curso mais rentável com muitas vendas(95 vendas). 
- O segundo curso mais rentável é o de "Cloud Computing com AWS" apesar das poucas vendas(37 vendas).
- O curso menos rentavel é o de "Segurança da Informação: Fundamentos" com apenas 15 vendas, ficando atrás do curso de "DevOps: Integração e Entrega Continua" com 14 vendas.
- O curso de "Desenvolvimento Web com HTML e CSS" é o segundo com mais vendas(75 vendas) e o terceiro mais rentavel. É também o curso com o maior desvio padrão.


