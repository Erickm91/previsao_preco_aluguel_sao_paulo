# 🏠 Predição de Aluguéis em São Paulo

Projeto de Ciência de Dados focado na previsão de valores de aluguel na cidade de São Paulo utilizando algoritmos de Machine Learning.

## 📌 Objetivo
Desenvolver um modelo capaz de estimar o valor de aluguel de imóveis com base em suas características, auxiliando na análise de mercado e tomada de decisão.

## 🧠 Modelos Utilizados
Foram testados diferentes algoritmos de regressão:

- Decision Tree  
- Linear Regression  
- XGBoost  
- Gradient Boosting  
- KNN (K-Nearest Neighbors)  

Todos os modelos foram aplicados utilizando um pipeline com etapa de pré-processamento e treinamento.

## 📊 Avaliação dos Modelos (MAE)
A métrica utilizada foi o **MAE (Mean Absolute Error)**:

| Modelo              | MAE    |
|---------------------|--------|
| Decision Tree       | 722.24 |
| Linear Regression   | 840.15 |
| XGBoost             | **703.35** |
| Gradient Boosting   | 802.12 |
| KNN                 | 735.33 |

## 🚀 Modelo Final
O modelo escolhido foi o **XGBoost**, por apresentar o menor erro absoluto médio (MAE), indicando melhor desempenho na **previsão dos valores de aluguel**.

Após a seleção, o modelo passou por ajuste de hiperparâmetros para otimização dos resultados.

## ⚙️ Pipeline
- Pré-processamento dos dados
- Treinamento dos modelos  
- Avaliação com MAE  
- Seleção do melhor modelo  
- Otimização com hiperparâmetros  

## 📈 Tecnologias Utilizadas
- Python  
- Pandas  
- Scikit-learn  
- XGBoost  

## 📎 Conclusão
O projeto demonstra a aplicação prática de técnicas de Machine Learning em um problema real de regressão, destacando a importância da comparação entre modelos e da otimização para obtenção de melhores resultados.