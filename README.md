# Redes-Neurais
Repositório para incluir meu aprendizado em Redes Neurais Artificiais

--------------------

1º Projeto Perceptron Bancário

Este projeto aplica o Perceptron Simples, uma rede neural básica de classificação, para analisar dados bancários de clientes e prever se o perfil é considerado “bom” ou “mau”. O modelo é implementado com a biblioteca scikit-learn.

Como Funciona:

Carregamento dos dados: O dataset bancario.csv é lido do Google Drive. Ele contém informações de clientes, incluindo renda, dívida e classe (bom/mau).

Preparação dos dados:

As colunas Renda e Dívida são usadas como variáveis de entrada (X).
A coluna Classe é convertida em valores numéricos: bom = 1, mau = -1.
Os dados são normalizados para ficarem entre 0 e 1.
Visualização inicial: É gerado um gráfico de dispersão para verificar se os dados são linearmente separáveis.
Divisão treino/teste: Os dados são separados em 70% para treino e 30% para teste.
Treinamento do modelo: O Perceptron é treinado com taxa de aprendizado (eta0 = 0.1) e até 100 iterações.

Avaliação:

Calcula a acurácia nos conjuntos de treino e teste.
Gera relatório de classificação com precisão, recall e f1-score.
Exibe a matriz de confusão para visualizar os acertos e erros.

Testes com novos exemplos:

Cliente com renda alta e dívida baixa → previsto como bom.
Cliente com renda baixa e dívida alta → previsto como mau.

Características:

Usa um modelo simples de rede neural para classificação binária.
Permite visualizar a separação dos dados e interpretar os resultados.
Inclui métricas e gráficos para avaliar o desempenho.
Demonstra como aplicar aprendizado de máquina em um problema real de análise de crédito.

Resultado Final:  
O código treina um Perceptron para classificar clientes como bom ou mau, avalia o desempenho com métricas e gráficos, e testa previsões em exemplos novos, mostrando como o modelo pode ser usado em cenários bancários.

---------------------------------

2º Projeto Perceptron Iris

Este projeto aplica o Perceptron Simples, uma rede neural básica de classificação, ao famoso dataset Iris, focando na distinção entre duas espécies: Iris-setosa e Iris-versicolor. O modelo é implementado com a biblioteca scikit-learn.

Como Funciona:

Carregamento dos dados: O dataset irisMLP.csv é lido do Google Drive.

Preparação dos dados:

São usadas as 100 primeiras amostras do dataset.
A coluna de classe é convertida em valores numéricos: Iris-setosa = -1, Iris-versicolor = 1.

As quatro variáveis de entrada (comprimento e largura de sépala e pétala) são normalizadas entre 0 e 1.

Visualização inicial: É gerado um gráfico de dispersão para verificar se as amostras são linearmente separáveis.

Divisão treino/teste: Os dados são separados em 70% para treino e 30% para teste.

Treinamento do modelo: O Perceptron é treinado com taxa de aprendizado (eta0 = 0.0001) e regularização (alpha = 0.1).

Avaliação:

Calcula a acurácia nos conjuntos de treino e teste.
Gera relatório de classificação com precisão, recall e f1-score.
Exibe a matriz de confusão para visualizar os acertos e erros.

Testes com novos exemplos: São feitas previsões em amostras individuais já normalizadas para verificar se o modelo classifica corretamente.

Características:

Demonstra o uso do Perceptron em um dataset clássico de aprendizado de máquina.
Mostra como transformar classes textuais em valores numéricos para treinamento.
Inclui métricas e gráficos para avaliar o desempenho do modelo.
Permite testar previsões em exemplos novos para validar a generalização.

Resultado Final:  
O código treina um Perceptron para distinguir entre Iris-setosa e Iris-versicolor, avalia o desempenho com métricas e gráficos, e testa previsões em amostras individuais, mostrando como o modelo pode ser aplicado em problemas de classificação de dados biológicos.
