# Modelo de Regresión Lineal

Este proyecto implementa un modelo de regresión lineal para predecir puntuaciones de exámenes en función de las horas de estudio. Se realiza un análisis exploratorio de datos (EDA), entrenamiento del modelo, evaluación con métricas de error y validación de residuos.

## Ejecución del Proyecto

1. Instalar las dependencias con `pip install -r requirements.txt
`.
2. Ejecutar el archivo `.ipynb` para el análisis de datos y el entrenamiento del modelo.
3. Iniciar la API con el siguiente comando:
   ```sh
   uvicorn api_modelo_regressao:app --reload
   ```

---

# Linear Regression Model

This project implements a linear regression model to predict exam scores based on study hours. It includes exploratory data analysis (EDA), model training, error metric evaluation, and residual validation.

## Project Execution

1. Install dependencies with `pip install -r requirements.txt
`.
2. Run the `.ipynb` file for data analysis and model training.
3. Start the API with the following command:
   ```sh
   uvicorn api_modelo_regressao:app --reload
   ```

---

# Projeto de Modelo de Regressão Linear

## Descrição

Este projeto implementa um modelo de regressão linear para prever a pontuação em testes com base no tempo de estudo. Ele realiza uma análise exploratória dos dados (EDA), treina um modelo de regressão linear, avalia seu desempenho e salva o modelo treinado para uso futuro.

## Tecnologias Utilizadas

- Python
- Scikit-Learn
- Pandas
- Seaborn
- Matplotlib
- Statsmodels
- SciPy
- Pingouin
- Joblib
- Uvicorn

## Estrutura do Projeto

- **datasets/**: Contém o conjunto de dados utilizado.
- **api_modelo_regressao.py**: Implementa uma API para interagir com o modelo treinado.
- **modelo_regressao.pkl**: Arquivo salvo do modelo treinado.
- **notebook.ipynb**: Contém o código de análise e treinamento do modelo.

## Como Executar o Projeto

1. Instale as dependências usando `pipenv`:

   ```sh
   pip install -r requirements.txt
   ```

2. Execute o notebook para carregar os dados, treinar e validar o modelo.
3. Inicie a API para fazer previsões com o modelo:
   ```sh
   uvicorn api_modelo_regressao:app --reload
   ```

## Funcionalidades

- Carregamento e análise exploratória dos dados.
- Treinamento de um modelo de regressão linear.
- Avaliação de desempenho do modelo por meio de métricas.
- Validação da distribuição dos erros do modelo.
- Predição de pontuação com base no tempo de estudo.
- API para interação com o modelo salvo.
