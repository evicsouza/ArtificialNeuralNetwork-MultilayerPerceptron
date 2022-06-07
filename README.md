PROJETO II – REDES NEURAIS

Considere a base de dados “diabetes”, disponível em https://datahub.io/machine-
learning/diabetes. Você deverá aplicar esta base de dados a uma rede neural Multilayer

Perceptron, a fim de classificar corretamente os dados apresentados quanto ao teste positivo
ou negativo para diabetes.
Para esta base de dados, é importante fazer a normalização dos dados para deixá-los dentro de

uma mesma escala. Se considerar necessário, você poderá fazer outras adaptações para o pré-
processamento da base de dados.

Separe a base de dados em dois conjuntos: treino (75%) e teste (25%). O subconjunto de treino
será utilizado para ajustar os pesos da rede neural, e o subconjunto de teste será utilizado
apenas para avaliar a capacidade de generalização da rede. Atenção para deixar os subconjuntos
com a mesma proporção de testes positivos e negativos para diabetes, a fim de não influenciar
nos resultados.
Treine e teste a rede por no mínimo 30 execuções. Plote um gráfico com a evolução média do
erro médio quadrático ao longo das épocas, para avaliar qual a quantidade de épocas ideal para
este problema.

Avalie também a taxa de aprendizagem (0.1, 0.01 e 0.001) e a quantidade de neurônios da
camada escondida (3, 5 e 7). Para isso, você poderá plotar um gráfico com a evolução média (30
execuções) do erro médio quadrático ao longo das épocas variando os respectivos parâmetros,
para identificar a influência do comportamento de cada um.
