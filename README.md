# Classificador de doença cardíaca

Classificação da existência de doença cardíaca usando algoritmos de Machine Learning. A ferramenta é feita para desenvolver o meu aprendizado
na utilização de vários algoritmos de machine learning.

## Dataset
Utilizei um dataset público com indicadores de doença cardíaco que pode ser encontrado no site Kaggle. Pode acessar o dataset nas referências.

## Algoritmos
Utilizei três algoritmos como um teste para treinar a inteligência artificial. Utilizei o mesmo dataset para testar todos os algoritmos e no final, comparei os três modelos com suas respectivas acurácias.

### Regressão Logística
A regressão logística é um método de análise estatística usado para modelar a relação entre uma variável de saída binária (como sim/não, 0/1) e uma ou mais variáveis independentes. Ao contrário da regressão linear, a regressão logística não visa prever valores contínuos, mas sim estimar a probabilidade de um evento pertencer a uma das duas classes. Ela utiliza uma função logística para transformar uma combinação linear das variáveis independentes em uma probabilidade, garantindo que a saída esteja dentro do intervalo de 0 a 1.

<img src="/imgs/logisticRegression.png" alt="accuracy matrix of Logistic Regression" width="400" height="300">

### Floresta Aleatória
É um algoritmo de aprendizado de máquina que constrói múltiplas árvores de decisão durante o treinamento e as combina para realizar previsões mais precisas e robustas. Cada árvore é treinada em uma amostra aleatória dos dados e toma decisões independentemente. A previsão final da Floresta Aleatória é determinada pela combinação das previsões individuais das árvores, seja através de votação ou média. 

<img src="/imgs/RandomForest.png" alt="accuracy matrix of Random Forest" width="400" height="300">

### Árvore de Decisão
Uma árvore de decisão é uma representação gráfica e lógica de um processo de tomada de decisão. No contexto do aprendizado de máquina, ela é um algoritmo que constrói uma estrutura hierárquica de perguntas e respostas para classificar ou prever dados. Cada nó interno da árvore corresponde a uma pergunta sobre uma característica dos dados, e cada ramo representa uma possível resposta à pergunta. Ao seguir o caminho da raiz até uma folha da árvore, uma série de decisões é tomada para atribuir uma categoria ou valor previsto ao dado. As árvores de decisão são fáceis de entender e interpretar, tornando-as valiosas para tarefas de classificação e regressão, enquanto sua flexibilidade permite lidar com diferentes tipos de dados e padrões complexos.

<img src="/imgs/decisionTree.png" alt="accuracy matrix of Decision Tree" width="400" height="300">

### Comparação entre os algoritmos
No gráfico abaixo. podemos notar uma grande semelhança de acurácia dos algoritmos usados para os testes. Nesse caso, podemos analisar outros fatores como escalabilidade e quantidade de poder computacional que possamos precisar como outros pontos para escolher a melhor forma de atuar.

<img src="/imgs/comparison.png" alt="Comparison between the algorithms" width="400" height="300">

## Referências

Kaggle - <a href="https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset">dataset</a>
