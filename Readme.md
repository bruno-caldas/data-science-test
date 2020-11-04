# Data Science

## O problema - 

Descrição aqui   

### Pandas

1. Importe a biblioteca ```Pandas``` as leia o arquivo ```Ecommerce Purchases.csv```

1. Quantas linhas e colunas o dataframe tem? Quais os datatypes?

1. Quais foram os 5 ```Purchase Price``` mais altos e mais baixos?

1. Quantas pessoas tem no ```Job``` o título aparece ```Scientist```?

1. Quantas pessoas tem ```American Express``` como CC Provider E fizeram compras acima de $95?

1. Quais foram os 5 dominios mais populares (```gmail.com, yahoo.com```)?

### Machine learning

1. Usando o dataset ```advertising.csv``` faça uma analise exploratória dos dados, coloque seus comentários e o que achou interessante em sua análise.

1. Crie um gráfico de dsitribuição com KDE do  ```Daily Time spent on site``` vs. ```Age```. Quais suas conclusões?

1. Crie um pairplot com HUE definido como ```Clicked on Ad```. Quais suas conclusões?

#### Predição da variável resposta 'Clicked on Ad'

1. Separe os dados para treino e teste.

1. Escolha o modelo de predição. Por que foram escolhidos esses modelos ? Explique resumidamente o que fazem.

1. Quais métricas utilizou para treinar e validar a performance do modelo?

1. Calcule os erros dos modelos. Quais erros foram calculados, explique resumidamente o que eles representam. Plote a ```Curva ROC``` e Calcule o ```AUC```.

1. Escolha o melhor modelo. Aplique o ```Cross Validation com kfold = 10``` e explique o que é.

1. Qual foi a média do erro obtido com o ```Cross Validation```?

### Procedure

1. Start a git clone repository with ```git clone https://github.com/grupofleury-stefanospindola/data-science-test.git```

### Training tool usage

1. Install Python 3 and cd to the solution folder
1. Run ```virtualenv env```
1. Run ```. env/bin/activate``` (commands might differ depending on your OS)
1. Run ```pip3 install -r requirements.txt```
1. Run ```python3 train.py data/```

### Evaluation tool usage

1. Install Python 3 and cd to the solution folder
1. Run ```virtualenv env```
1. Run ```. env/bin/activate``` (commands might differ depending on your OS)
1. Run ```pip3 install -r requirements.txt```
1. Run ```python3 evaluate.py data/```