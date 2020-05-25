# Notas ENADE 2014

![teste](https://img.shields.io/badge/Type-Beginner-success)
![Type Regression](https://img.shields.io/badge/Type-Regression-yellow.svg)

Neste trabalho, utilizei a base de dados do ENADE 2014 para criar modelos simples de regressão para prever a nota final do aluno. A nota varia entre 0 e 100.

A base de dados está em formato zip por limitações de tamanho, mas também pode ser obitda no site oficial do ENADE: http://inep.gov.br/microdados

Também é possível analisar quais fatores impactam mais na nota final do aluno. Nota-se, por exemplo, que a escolaridade dos pais tem alta correlação com a nota final.

Foram utilizados vários algoritmos diferentes como: Regressão Linear, Random Forest, XGBoost, lightGBM

A métrica para avaliação foi o RMSE (Root Mean Square Error) e o melhor resultado foi RMSE = 12.23 com o lightGBM




#### Dependencias no arquivo Requirements.txt

