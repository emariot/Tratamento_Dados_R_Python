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

## Alguns exemplos de gráficos com R, com o pacote ggplot2.
---
* BarPlot

<a href="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/barplot.png"><img src="https://github.com/emariot/Tratamento_Dados_R_Python/blob/main/R/img/barplot.png" align="left" height="450" width="450" ></a>
