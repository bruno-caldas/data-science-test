# Data Science

## O problema - Probabilidade do não comparecimento dos pacientes na unidade de atendimento de exames clinicos.

Todos os agendamentos de exames são feitos previamente pelos canais de atendimento, como telefone ou mensagens. 
Um dos grandes problemas que atingem a maior parte das empresas de saúde é quando um paciente agenda um exame e não comparece, chamamos esse evento de Noshow.

Isso gera um grande transtorno nas atividade das unidades e um prejuizo enorme, com medicos e atendimento parado aguardando o paciente, mas também com custos referentes ao funcionamento da unidade.

Para ajudar a resolver este problema propomos um problema de classificação de Noshow, que consiste em determinar se o paciente ira comparecer ou não na unidade de atendimento para realizar o exame que ele agendou.

Os dados estão no arquivos seguinte:

    *   dados.csv

Com base nos dados fornecidos e outras fontes que achar confiáveis:
    *   Quais as ações podem reduzir a ocorrência do Noshow? 
    *   Quais os principais motivos do Noshow?
    *   Faça uma analise exploratória dos dados e comente o que você encontrou.
    *   Separe os dados para treino e teste, e faça a predição de quais agendamentos serão Noshow.
    *   Comente e explique as tecnicas utilizadas (porque utilizou elas?), os insights que ajudariam o negocio a reduzir o problema de Noshow a partir da sua análise exploratória e modelagem.
    *   Grave um audio ou video ou texto (também Jupyter notebook ou .py) para nos enviar seus resutados e conclusões.

### Informações dos Atributos

- Dia semana agendamento: Dia da semana que o exame foi agendado

- Ano agendamento: Ano que o exame foi agendado

- Mes agendamento: Mes que o exame foi agendado

- Hora agendamento: Hora que o exame foi agendado

- Dia mes agendamento: Dia do mes que o exame foi agendado

- Dia semana atendimento: Dia da semana do atendimento ao paciente

- Ano atendimento: Ano do atendimento ao paciente

- Mes atendimento: Mes do atendimento ao paciente

- Hora atendimento: Hora do atendimento ao paciente

- Dia mes atendimento: Dia do mes do atendimento ao paciente

- Secao: 

- Medico preferencial:

- Renda Provavel: Renda baseada na região do paciente

- MicroArea: 

- Diretoria:

- Cod convenio: Código do convênio  

- Codigo exame: Código do exame que será realizado

- Idade: Idade do paciente

- Tempo medio de agendamento: Tempo médio do processo de agendamento

- Unidade: Unidade de atendimento
 
- Bairro: Bairro de atendimento

- Feminino: A pessoa é do sexo feminino ou não

- No Show: A pessoa compareceu ou não no exame [label]

### Entregáveis

A solução para o problema proposto deve ser entregue com as seguintes caracteristicas:
    


### Pandas

1. Importe a biblioteca ```Pandas``` as leia o arquivo ```Ecommerce Purchases.csv```

1. Quantas linhas e colunas o dataframe tem? Quais os datatypes?

1. Quais foram os 5 ```Purchase Price``` mais altos e mais baixos?

1. Quantas pessoas tem no ```Job``` o título aparece ```Scientist```?

1. Quantas pessoas tem ```American Express``` como ```CC Provider``` e fizeram compras acima de $95?

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