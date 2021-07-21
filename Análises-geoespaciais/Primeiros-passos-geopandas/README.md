# Primeiros passos em análises geoespaciais e geopandas

As análises geoespaciais agrupam, manipulam e apresentam informações dos Sistemas de Informação Geográficos (SIG ou GIS, em inglês) com o objetivo de extrair insights que seriam inacessíveis de outra forma. Dito isso, existem aplicações para diversas áreas como segurança pública, sistemas rodoviários e agropecuária.
Dentre as muitas aplicações desta área, uma que me interessa muito são as aplicações na saúde. 

Combinando dados dos sistemas de saúde com informações geográficas podemos rastrear infecções, descobrir hotspots para algumas doenças e também avaliar quais regiões carecem de atenção hospitalar, por exemplo.

Para começar nessa área usando python, um ótimo pacote é geopandas. Como o nome sugere, o geopandas é um pacote que tem funcionalidades muito parecidas com o pandas, mas é focado para análises geoespaciais. Nesse exemplo, vamos analisar os índices de vacinação contra COVID-19 no estado do PR.


![img](https://raw.githubusercontent.com/souzajvp/educational/main/An%C3%A1lises-geoespaciais/Primeiros-passos-geopandas/Percentual_imunizados.png)


## Arquivos presentes neste diretório
|                          Nome do arquivo                          |                                              Descrição                                             |                                                       Fonte                                                       |
|:-----------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| Vacinação_contra_COVID_19_no_Paraná_Uma_análise_geoespacial.ipynb |                            Notebook com as análises mencionadas no post                            |                                                    Este projeto                                                   |
|               Preparando_os_dados_para_análise.ipynb              |         Notebook com o passo-a-passo para preparar os banco vacinacao_populacao_parana.csv         |                                                    Este projeto                                                   |
|                       PR_Municipios_2020.zip                      |                          Malha territorial dos municípios do estado do PR                          | https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html?=&t=downloads |
|                           PR_UF_2020.zip                          |                                        Malha estadual do PR                                        | https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html?=&t=downloads |
|                   vacinacao_populacao_parana.csv                  |        Arquivo csv contendo informações populacionais e de vacinação da população do Paraná        |                                                      Diversas                                                     |
|                        pop_parana_2010.csv                        | Arquivo .csv contendo informações populacionais dos municípios do PR de acordo com o Censo de 2010 |                          http://tabnet.datasus.gov.br/cgi/deftohtm.exe?ibge/cnv/poppr.def                         |
|                  vacinacao_covid_17_07_2021.xlsx                  |                     Dados de vacinação de COVID-19, baixados no dia 17/07/2021                     |                    https://qsprod.saude.gov.br/extensions/DEMAS_C19Vacina/DEMAS_C19Vacina.html                    |
|                                                                   |                                                                                                    |                                                                                                                   |
