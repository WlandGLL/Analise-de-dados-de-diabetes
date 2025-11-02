# Introdução

Este projeto realiza uma análise exploratória e preditiva da base de dados sobre diabetes na população Pima, uma comunidade indígena norte-americana.
O objetivo é entender os fatores que influenciam o desenvolvimento da diabetes tipo 2 e construir um modelo de aprendizado de máquina capaz de prever a ocorrência da doença.
A base está disponível no Kaggle – (https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## Etapas do Projeto
1️⃣ Carregamento e inspeção dos dados:

Verificação de linhas, colunas e tipos de dados
Confirmação de ausência de valores nulos

2️⃣ Tratamento de dados:

Identificação de valores zero inválidos em colunas como Glucose e BMI
Substituição por valores medianos
Exclusão da variável Insulin devido à alta taxa de zeros (≈49%)

3️⃣ Análise exploratória:
Visualizações com matplotlib e seaborn

4️⃣ Modelagem preditiva

Modelo: Regressão Logística
Divisão dos dados: 70% treino / 30% teste
Acurácia obtida: ≈ 74%

5️⃣ Teste com novo paciente

Foi realizado um teste de predição com dados fictícios, e o modelo retornou:
Previsão: 0 (Sem Diabetes)
Probabilidade: [0.66, 0.33]

🧠 Tecnologias Utilizadas

Python 3
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

