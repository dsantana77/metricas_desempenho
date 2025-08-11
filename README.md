# metricas_desempenho
Avaliação de Modelos de Classificação com Métricas de Desempenho

## Objetivo:
Treinar um modelo de classificação (por exemplo, usando LogisticRegression ou RandomForest) e calcular as principais métricas para interpretar seu desempenho.

## projeto_metricas/
│

├── data/                # Dataset usado (pode ser CSV real ou gerado)

├── metricas.py          # Funções para cálculo das métricas

├── treino_modelo.py     # Treinamento do modelo e uso das métricas

├── requirements.txt     # Bibliotecas necessárias

└── README.md            # Documentação


## Fluxo básico do projeto
Coleta/geração dos dados

Usar um dataset pronto (sklearn.datasets.load_breast_cancer, load_iris, ou outro binário).

Divisão em treino e teste

train_test_split

Treinamento do modelo

Logistic Regression ou Random Forest.

Predição e cálculo das métricas

Usar sklearn.metrics para acurácia, precisão, recall, f1-score.

Especificidade = TN / (TN + FP) (calculada manualmente a partir da confusion matrix).

Exibição dos resultados

Mostrar no terminal e também em tabela formatada.
