# Projeto: "Análise de Fatores que Influenciam a Precificação de Prêmios em Seguros"

## Objetivos: 
--Avaliar se a idade dos segurados influencia a frequência de sinistros. 
--Verificar se a frequência de sinistros impacta o valor do prêmio cobrado pelas seguradoras. 
--Testar modelos de regressão, incluindo modelos com e sem redução de dimensionalidade (PCA), para avaliar a robustez e generalização das conclusões.

## Metodologia:
--Análise Exploratória de Dados (EDA)
--Modelos com e sem PCA
--Regressão Linear Simples e Regressão Linear Múltipla

## Conjunto de dados:
--Source: Kaggle - "Insurance Dataset Based on Real-World Statistics" - https://www.kaggle.com/datasets/samialyasin/insurance-data-personal-auto-line-of-business 
--Size: 10.000 linhas × 27 colunas

## Features & Workflow:
--Limpeza e Pré-processamento dos Dados (verificação de valores ausentes)
--Análise Exploratória dos Dados (EDA) utilizando Seaborn e Matplotlib
--Treinamento de Modelo utilizando Regressão Linear do Scikit-learn
--Avaliação do Modelo (R², RMSE, MAE)

## Requisitos
--Python 3.8+
--pandas, numpy, matplotlib, seaborn
--scikit-learn, statsmodels
