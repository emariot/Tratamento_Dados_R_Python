# Tratamento_Dados_R_Python

Estudo de tratamento de dados com R e Python 

Porque os dados possuem problemas e devem ser tratados:

* Sistemas de operações e DBs sem restrição de entrada (formatos fora do padrão),
* Atualizações diretas em DBs (sistema sem integridade),
* Sistemas antigos, codificados diretamente,
* Inconsistência nos processos de carga:
   * Origem de informação diversa, não padronizado
   * Mudança no processo (atualização de sistemas e carga de dados)
   * Erros no processo

Operação Vs Analítico

   * Na operação o dado em seu formato individual não pode ser alterado para um valor padrão 
       * Ex.: A data de nascimento de um cliente de plano de saúde que altera o valor do plano.
   * No analítico, o dado não tem valor individual, mas coletivo. Deve ser corrigido pelo "bem" do modelo:
       * Ex,: Prever o custo de clientes com determinadas características e o modelo não permite valores faltantes. Alterar a idade faltante para a mediana não deve afetar a operação e não pode causar enviesamento no modelo.
       
Problemas mais encontrados nos dados:
    
   * Duplicidade
   * Consistência
   * Completude
   * Conformidade
   * Integridade

** Eventualmente substituimos variaveis categóricas pela moda e quantitativas pela mediana dos dados.

## R/Gráficos.ipynb
### Alguns exemplos de gráficos com R, com o pacote ggplot2
---

|    BarPlot   |
| ------------ |
<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/barplot.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/barplot.png" align="left" height="450" width="650" ></a>|

|    BoxPlot   |
| ------------ |
<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/boxplot.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/boxplot.png" align="left" height="450" width="650" ></a>|

| Histograma 1 | Histograma 2 |
| ------------ | ------------- |
<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/hist.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/hist.png" align="center" ></a> | <a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/histogram.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/histogram.png" align="center" ></a>

|   LineChart  |
| ------------ |
<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/linechart.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/linechart.png" align="left" height="450" width="650" ></a>|

| ScatterPlot  |
| ------------ |
<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/scatterplot.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/scatterplot.png" align="left" height="450" width="650" ></a>|

|    Treemap   |
| ------------ |
<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/treemap.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/treemap.png" align="left" height="450" width="650" ></a>|

## R/Tratamento_Iris.ipynb
### Pequeno tratamento no dataset iris
---
  1. Sumarizar os dados com as médias de cada coluna de acordo com a categoria
  <a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/iris_1.PNG"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/iris_1.PNG"></a>



  2. Extrair o valor inteiro de uma das colunas decimais
   
