# Desafio Kaggle de detecção de cliques falsos (TalkingData)

>Fui apresentado a esse desafio pela *Data Science Academy* como parte de seu programa curricular.

A proposta do desafio é encontrar uma forma de detectar cliques falsos em anúncios de aplicativos. Para isso foi disponibilizado um dataset com quase 200 milhões de registros.

Página oficial do desafio: https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection

### Divisão do projeto

Esse projeto está dividido em 2 notebooks:

#### EDA (Exploratory Data Analysis)

https://nbviewer.jupyter.org/github/marcoayamada/td-click-fraud-detection/blob/master/EDA.ipynb - [[Github](https://github.com/marcoayamada/td-click-fraud-detection/blob/master/EDA.ipynb)]

#### Modelagem
https://nbviewer.jupyter.org/github/marcoayamada/td-click-fraud-detection/blob/master/Models.ipynb - [[Github](https://github.com/marcoayamada/td-click-fraud-detection/blob/master/Models.ipynb)]


No primeiro ha uma análise exploratória sobre os dados, bem como alguns padrões econtrados. No segundo há a criação de alguns modelos preditivos para solucionar o problema.

### Créditos

Na primeira versão desse projeto foi feita uma tentativa de resolução com a criação de dados sintéticos (SMOTE e ADASYN) a partir de uma amostra pequena do dataset, porém, essa abordagem não funcionou muito bem e então parti para o conjunto completo.

Muitas dificuldades apareceram, então, procurei e encontrei muita coisa boa no Kaggle. Duas fontes principais de consulta e estudo foram:

- https://www.kaggle.com/yuliagm/talkingdata-eda-plus-time-patterns
- https://www.kaggle.com/tunguz/xgboost-starter

Créditos totais aos dois tópicos!
