<h2 align=center> Análises da empresa Airbnb usando bibliotecas Python </h2>

![airbnb](https://github.com/EduardoSymph/Airbnb-Python/assets/134222436/fc72d2db-8baf-49ae-98b8-148db1ce32a5)

![Badge em Desenvolvimento](https://img.shields.io/badge/Projeto-Conclu%C3%ADdo-brightgreen) 

<h2>Descrição do projeto :memo:</h2>

Este projeto utiliza a base de dados pública da Airbnb, uma renomada empresa comunitária focada em aluguéis e hospedagens. Foram realizadas análises empregando a linguagem <b>Python</b> e bibliotecas especializadas como <b>Pandas, NumPy e MatPlotlib</b>. O objetivo principal é processar e visualizar os dados para extrair insights que podem ser úteis para stakeholders e entusiastas do setor.

<h2>Técnologias Utilizadas 🛠️</h2>

- ``Python``
- ``Jupyter Notebook``

<h2>Análises do Projeto 🧐</h2>

Após carregar os dados iniciais de um arquivo CSV, comecei a primeira leitura e análise dos dados. Para um entendimento mais aprofundado das análises realizadas, você pode acessar o Jupyter Notebook <a href="https://github.com/EduardoSymph/Airbnb-Python/blob/main/airbnb_analises.ipynb" target="_blank"> clicando aqui</a>. Alternativamente, se preferir, o arquivo .py está disponível e pode ser <a href="https://github.com/EduardoSymph/Airbnb-Python/blob/main/airbnb_analises.py" target="_blank"> acessado aqui</a>.

Iniciamos a análise focando na média dos aluguéis. Isso foi feito utilizando a função mean() em conjunto com a coluna 'price'. Após obter esse resultado inicial, a análise foi expandida com um groupby por regiões para obter especificidades mais detalhadas:

![image](https://github.com/EduardoSymph/Airbnb-Python/assets/134222436/bd7d3cd1-704f-42b9-aa6d-127d21537a73)

Conclusão: a maior média de preços está em Manhattan.

Na análise seguinte, foi verificado o valor da diária mais alta nas regiões da cidade de Nova York. Após identificar que mais de uma região apresentava valores semelhantes, optei por aplicar um gráfico de histograma, facilitando assim a visualização desses dados:

![image](https://github.com/EduardoSymph/Airbnb-Python/assets/134222436/edb3bda1-3051-480c-9ede-b1266a65d1a6)

Conclusão: Brooklyn, Manhattan e Queens dividem o maior aluguel diário (10 mil doláres).

Prosseguindo com as análises, o foco foi direcionado para identificar o maior valor de aluguel, segmentado por bairro e tipo de quarto.

![image](https://github.com/EduardoSymph/Airbnb-Python/assets/134222436/6ea71b2e-b665-4f2d-9655-30a8225c3e4b)

Conclusão: Existem notáveis diferenças de aluguéis do mesmo tipo de quarto, mas em regiões diferentes (em Allerton, um quarto do tipo Entire home/apt custa 450 dólares; em Arrochar, o valor já sobe para 625 dólares).

Por fim, foi realizado uma análise para determinar o menor valor de latitude em cada região. Para tornar essa comparação entre as regiões mais clara e acessível, os resultados foram apresentados em um gráfico de barras, facilitando a compreensão das diferenças de latitude mínima entre as diversas regiões.

![image](https://github.com/EduardoSymph/Airbnb-Python/assets/134222436/815cd9b7-d18f-4d79-b982-ed95ce103e6b)

Conclusão: Staten Island possuí a menor latitude dentre as regiões.

