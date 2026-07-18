# Predição de Teste de Cobb

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leandroveigadev/cobb-prediction-system/blob/main/notebooks/01_simulacao_cobb_mp23.ipynb)

Este projeto implementa um algo parecido com um (Sensor Virtual) utilizando Machine Learning para estimar o Teste de Cobb em tempo real. 
Solução desenvolvida para otimização de qualidade e redução de variabilidade em máquinas de papel.

## Valor de Negócio (Consultoria)
O teste de laboratório tradicional pode atrasar processos para gerar um resultado. Com este modelo, a operação tem um feedback **instantâneo**, permitindo:
* **Redução de Refugo:** Identificação imediata de desvios.
* **Otimização de Químicos:** Ajuste preciso na dosagem de amido e cola.
* **Estabilidade Operacional:** Menor variabilidade e maior velocidade de máquina segura.

## Inteligência do Modelo
* **Algoritmo:** XGBoost Regressor (Estado da arte para dados tabulares industriais).
* **Interpretabilidade (SHAP):** O modelo não é vazio. Utilizado valores SHAP para explicar quais variáveis (Vazão de Amido, Velocidade, Pressão de Vapor) estão impactando o Cobb em cada momento.

## Stack Tecnológica
* **Linguagem:** Python 3.12 (Ambiente Linux/Ubuntu)
* **Ambiente:** VS Code + Jupyter Notebooks
* **Principais Libs:** Pandas, Scikit-Learn, XGBoost, Plotly e SHAP.

