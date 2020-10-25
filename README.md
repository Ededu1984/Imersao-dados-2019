# Imersao-dados-2019
Analisando dados do ENEM 2019


A Imersão de dados da Alura Cursos Online foi realizada no mês de Outubro de 2020. O objetivo principal foi ajudar aqueles que tem interesse na área de dados a darem os primeiros passos na criação de um projeto de Data Science.

Uma amostra dos microdados disponíveis no site do INEP foi criada e disponibilizada no GitHub da Alura.

No geral observou-se um grande impacto da renda social que por sua vez impacta numa série de outros fatores que somados contribuem no desempenho dos inscritos.


## Ao longo do projeto foi possível observar a grande influência nas notas totais de algumas características como:

- Renda familiar
- Raça
- Tipo de escola que é uma consequência na maioria das vezes da renda familiar
- Internet e número de computadores na casa que também é um demonstrativo da renda familiar


Neste exame do ENEM houveram mais mulheres inscritas do que homens e as notas das mulheres foram ligeiramente um pouco melhores.

Algo interessante observado foi o número de desistências da prova após o primeiro dia de prova. O aumento de faltantes do primeiro dia de prova para o segundo foi de aproximandamente 18%.

20 % dos inscritos fizeram em uma cidade diferente da cidade de residência.

Nesta amostra apenas 4 alunos com 13 anos fizeram a prova.

Como é possível enxergar no mapa de calor a quantidade de participantes da região norte e centro oeste foi menor visualmente comparado com outras regiões do país.

Quanto aos modelos de Machine Learning, o melhor desempenho foi observado no XGBoost.

Três métricas foram escolhidas:

- R2 score - Erro quadrado

- RSME - Raiz quadrada do erro médio quadrado. Este tipo de métrica tem maior penalidade para error grandes e sofre mais com o impacto dos outliers.

- MSLE Raiz quadrada do erro médio logarítmo quadrado. Este tipo de métrica não se importa com a diferença absoluta, se importa somente com a diferença relativa

No geral pode-se concluir que a desigualdade social é explicitada claramente nos dados e que a mesma é um fator de grande peso no desempenho dos inscritos. Ainda assim, sempre existe outliers que demonstram que mesmo com a desigualdade existe aqueles que conseguem se superar e obter ótimos desempenhos.


Obs: As conclusões foram baseadas na amostra para poder representar a população de inscritos do ENEM 2019.

