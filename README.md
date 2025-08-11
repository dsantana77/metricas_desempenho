# metricas_desempenho
Avaliação de Modelos de Classificação com Métricas de Desempenho

# Projeto: Avaliação de Modelos de Classificação com Deep Learning
Fluxo
Dataset

Podemos usar um conjunto binário como Breast Cancer (sklearn) ou PIMA Indians Diabetes (muito usado para classificação binária).

Pré-processamento

Normalização das features (StandardScaler).

Divisão treino/teste.

Construção da rede neural

Arquitetura simples (entrada → camadas densas → saída sigmoide).

Treinamento

Função de perda: binary_crossentropy.

Otimizador: adam.

Cálculo das métricas

Usar confusion_matrix para sensibilidade, especificidade.


