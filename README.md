# Classificador de doença cardíaca

Classificação da existência de doença cardíaca usando algoritmos de Machine Learning. A ferramenta é feita para desenvolver o meu aprendizado
na utilização de vários algoritmos de machine learning.

## Dataset
Utilizei um dataset público com indicadores de doença cardíaco que pode ser encontrado no site Kaggle. Pode acessar o dataset nas referências.

## Algoritmos
Utilizei três algoritmos como um teste para treinar a inteligência artificial. Utilizei o mesmo dataset para testar todos os algoritmos e no final, comparei os três modelos com suas respectivas acurácias.

### Regressão Logística
A regressão logística é um método de análise estatística usado para modelar a relação entre uma variável de saída binária (como sim/não, 0/1) e uma ou mais variáveis independentes. Ao contrário da regressão linear, a regressão logística não visa prever valores contínuos, mas sim estimar a probabilidade de um evento pertencer a uma das duas classes. Ela utiliza uma função logística para transformar uma combinação linear das variáveis independentes em uma probabilidade, garantindo que a saída esteja dentro do intervalo de 0 a 1.

<img src="/imgs/logisticRegression.png" alt="accuracy matrix of LogisticRegression" width="400" height="300">

### Floresta Aleatória
É um algoritmo de aprendizado de máquina que constrói múltiplas árvores de decisão durante o treinamento e as combina para realizar previsões mais precisas e robustas. Cada árvore é treinada em uma amostra aleatória dos dados e toma decisões independentemente. A previsão final da Random Forest é determinada pela combinação das previsões individuais das árvores, seja através de votação ou média. 

<img src="/imgs/logisticRegression.png" alt="accuracy matrix of LogisticRegression" width="400" height="300">
