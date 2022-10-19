# Predicao-de-Spam
Obter o melhor classificador, baseado em instâncias, usando o algoritmo do vizinho mais próximo (knn).

Dataset: 
  * csv contendo 5172 linhas, onde cada linha é um e-mail, e tem 3002 colunas, onde cada coluna é um atributo.
  * A última coluna chamada prediction é a classe e diz se é 1 (spam) ou 0 (não é spam);
  * A primeira coluna é o nome do e-mail, representado por um número (id);
  * O restante das colunas são atributos preditivos, ou seja, todas as palavras em inglês que estão nos e-mails (ex: the, to, for) e quantas vezes elas aparecem;
  * Resultado: data frame ou vetor mostrando a classe prediction e a acurácia final do conjunto de teste;
  * link: https://www.kaggle.com/balaka18/email-spam-classification-dataset-csv

