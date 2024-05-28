# Previsão de Condições Ambientais Marítimas

## Descrição do Projeto

Este projeto foi desenvolvido para prever condições ambientais marítimas usando técnicas de Machine Learning, com o objetivo de antecipar eventos prejudiciais para a vida marinha. As principais etapas do projeto incluem exploração de dados, levantamento de hipóteses, criação e treinamento de modelos, validação e conclusão.

## Etapas do Projeto

### 1. Exploração de Dados

- **Carregamento dos Dados**: Carregamos o conjunto de dados contendo informações ambientais marítimas.
- **Limpeza de Dados**: Realizamos a limpeza dos dados para remover valores ausentes e tratar outliers.
- **Análise Exploratória**: Exploramos os dados usando visualizações e estatísticas descritivas para entender melhor as características e padrões presentes.

### 2. Levantamento de Hipóteses

- **Identificação de Padrões**: Com base na análise exploratória, levantamos hipóteses sobre como diferentes fatores ambientais, como temperatura, salinidade e níveis de poluição, podem afetar a vida marinha.
- **Definição de Variáveis**: Selecionamos as variáveis mais relevantes para a criação dos modelos preditivos.

### 3. Criação e Treinamento de Modelos

- **Seleção de Modelos**: Escolhemos diversos algoritmos de Machine Learning, como RandomForestRegressor e Support Vector Machine (SVM), para nossos experimentos.
- **Divisão de Dados**: Dividimos o conjunto de dados em conjuntos de treinamento e teste para avaliar a performance dos modelos.
- **Treinamento de Modelos**: Treinamos os modelos usando os dados de treinamento e ajustamos hiperparâmetros para otimizar o desempenho.

### 4. Validação

- **Avaliação de Modelos**: Avaliamos os modelos usando métricas como Mean Squared Error (MSE) e R² para modelos de regressão e precisão, recall e F1-Score para modelos de classificação.
- **Validação Cruzada**: Utilizamos validação cruzada para garantir que os modelos sejam robustos e generalizem bem para novos dados.

### 5. Conclusão

- **Resultados**: Os modelos desenvolvidos mostraram-se eficazes em prever condições ambientais marítimas. Em particular, o RandomForestRegressor obteve um MSE de aproximadamente 0.028 e um R² de 0.84.
- **Insights**: Identificamos que variáveis como temperatura e níveis de poluição têm um impacto significativo na vida marinha, permitindo a antecipação de eventos prejudiciais e a implementação de estratégias de mitigação.
