# Fundamentos de Machine Learning

Este projeto foi baseado a partir do Notebook do kaggle [Chess Evaluations](https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations?select=chessData.csv) e tem o objetivo de analisar os resultados dos otimizadores AdamW e Stochastic gradient descent (SGD) utilizados com conjunto de valores para os paramêtros quantidade de dados (MAX_DATA), tamanho da janela de treinamento (BATCH_SIZE) e quantidade de épocas (EPOCHS).


## Dados
- [chessData.csv](https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations?select=chessData.csv);
- [random_evals.cvs](https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations?select=random_evals.csv);
- [tactic_evals.csv](https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations?select=tactic_evals.csv)


## Dependências
| Biblioteca        | Versão       |
|-------------------|--------------|
| torch             | 1.11.0+cu113 |
| numpy             | 1.22.4       |
| scikit-learn      | 1.1.1        |
| chess             | 1.9.1        |
| pandas            | 1.4.2        |
| matplotlib        | 3.5.2        |
| matplotlib-inline | 0.1.3        |
| plotly            | 5.8.2        |


## Autores
| **Nome**        | **Github**                                                    |
|-----------------|---------------------------------------------------------------|
| Rubens Cividati | [Cividati](https://github.com/Cividati)    |
| Renan Dias      | [RenanDias12](https://github.com/renandias12) |