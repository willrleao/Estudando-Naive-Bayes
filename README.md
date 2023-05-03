# Estudando Naive Bayes

Este repositório contém notebooks e scripts com exemplos de como utilizar o algoritmo de classificação Naive Bayes em problemas de aprendizado de máquina.


`Naive Bayes BernoulliNB:`
```
                precision    recall  f1-score   support

             0       0.99      0.95      0.97       148
             1       0.91      0.97      0.94        80

      accuracy                           0.96       228
     macro avg       0.95      0.96      0.95       228
  weighted avg       0.96      0.96      0.96       228

  Number of mislabeled points out of a total 228 points : 10
  train_size=0.60,test_size=0.40
  
              precision    recall  f1-score   support

           0       0.92      0.96      0.94       320
           1       0.93      0.85      0.89       193

    accuracy                           0.92       513
   macro avg       0.92      0.91      0.92       513
weighted avg       0.92      0.92      0.92       513

Number of mislabeled points out of a total 513 points : 40
train_size=0.10,test_size=0.90
```

## Notebooks

- `exemplo_naive_bayes.ipynb`: exemplo básico de como utilizar o Naive Bayes com dados sintéticos.

## Scripts

- `naive_bayes.py`: implementação do algoritmo Naive Bayes.
- `utils.py`: funções auxiliares para pré-processamento dos dados.

## Requisitos

- Python 3.x
- Pandas
- Scikit-learn

## Como utilizar

Para executar o exemplo do notebook, basta executar o seguinte comando:


Para utilizar a implementação do algoritmo Naive Bayes em seu próprio projeto, basta importar o arquivo `naive_bayes.py` e utilizar a classe `NaiveBayes`.

## Contribuição

Contribuições são sempre bem-vindas! Caso tenha encontrado algum bug ou tenha uma sugestão de melhoria, por favor, abra uma issue ou submeta uma pull request.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
