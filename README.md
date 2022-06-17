# mpsp_hc_stj

## Os últimos 1000 HCs impetrados no STJ que interessam ao MPSP
### 17/06/2022

O presente notebook buscou obter os resultados dos HCs impetrados no STJ.

A análise foi feita a partir de dataset composto dos últimos 1000 HCs impetrados no STJ. O arquivo "csv" foi gerado pelo STJ no dia 17 jun. 2022.

O script também foi rodado em 17 jun. 2022 com o intuito de verificar quais HCs já possuíam decisões monocráticas. 

O codigo foi escrito em Python. Foram utilizadas as bibliotecas pandas (para as operações com o dataframe), matplotlib (para os gráficos), requests (para as requisições http ao site do STJ) e beautifulsoup (para a extração dos dados dos documentos html recuperados). A engine 'xlsxwriter' foi usada para gravar o arquivo Excel em unicode.
