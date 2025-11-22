# Análise de Dados das Lojas
1. Objetivo

Este projeto tem como objetivo analisar o desempenho de quatro lojas diferentes e identificar qual delas deve ser vendida, considerando variáveis como faturamento, categorias mais vendidas, avaliações dos clientes, produtos mais vendidos e frete médio.

A análise foi realizada utilizando Python, Pandas e Matplotlib.

2. Dados Utilizados

Foram fornecidos quatro arquivos contendo dados de vendas das lojas:

loja_1.csv

loja_2.csv

loja_3.csv

loja_4.csv

Cada arquivo inclui informações de produtos, categorias, preço, frete, avaliação do cliente e outros atributos relevantes.

3. Métricas Avaliadas
3.1 Faturamento Total

O faturamento foi calculado somando a coluna "Preço" de cada loja.

Resultados:

Loja 1: R$ 1.534.509,12

Loja 2: R$ 1.488.459,06

Loja 3: R$ 1.464.025,03

Loja 4: R$ 1.384.497,58

A Loja 4 apresenta o menor faturamento.

3.2 Categorias Mais Vendidas

As categorias mais vendidas foram identificadas por meio da contagem de produtos por categoria em cada loja.

As quatro lojas apresentam comportamento semelhante:

Móveis e Eletrônicos são as categorias com maior volume de vendas.

3.3 Avaliações dos Clientes

As médias de avaliação das lojas foram calculadas pela coluna "Avaliação da compra".

Resultados:

Loja 1: 4,00

Loja 2: 4,04

Loja 3: 4,05

Loja 4: 4,00

As avaliações são todas similares e não influenciam negativamente nenhuma loja.

3.4 Frete Médio

O custo médio de frete foi determinado a partir da coluna "Frete".

Resultados:

Loja 1: R$ 31,28

Loja 2: R$ 33,62

Loja 3: R$ 33,07

Loja 4: R$ 31,28

A Loja 4 não sofre com frete alto.

4. Gráficos Criados

Três gráficos foram gerados para facilitar a visualização:

Gráfico de barras – Faturamento total por loja.

Gráfico de pizza – Distribuição total das categorias mais vendidas.

Gráfico de linha – Frete médio por loja.

Os gráficos reforçam visualmente as diferenças entre as unidades.

5. Conclusão da Análise

Com base em todos os indicadores analisados, a Loja 4 apresenta o pior desempenho geral.

Principais motivos:

Menor faturamento entre as quatro unidades.

Mesma estrutura de vendas e categorias das demais lojas, mas com menor retorno financeiro.

Avaliação e frete compatíveis com as outras lojas, o que indica que o problema está no ticket médio ou estratégia de preços.

Recomendação final: A Loja 4 é a melhor candidata para ser vendida, pois apresenta menor lucratividade e menor potencial de crescimento dentro do conjunto analisado.

6. Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib

Google Colab

7. Como Executar

Abra o projeto no Google Colab ou Jupyter Notebook.

Importe os arquivos CSV das lojas.

Execute as células na ordem indicada.

Os gráficos serão exibidos automaticamente.
