O dataset trabalhado é o Breast Cancer Wisconsin Diagnostic Database, que incluí informações sobre tumores de câncer de mama, bem como rótulos de classificação como malignos ou benignos. O dataset tem 569 instâncias, ou dados, sobre 569 tumores e inclui informações sobre 30 atributos, ou características, tais como o raio do tumor, textura, suavidade, e área. 

O próposito desde código é construir um modelo simples de machine learning para utilizar as informações sobre tumores para prever se um tumor é maligno ou benigno.

A variável data representa um objeto Python que funciona como um dicionário. As chaves importantes do dicionário a considerar são os nomes dos rótulos de classificação (target_names), os rótulos reais (target), os nomes de atributo/característica (feature_names), e os atributos (data).

Para avaliar o desempenho de um classificador, você deve sempre testar o modelo em dados não visualizados. Portanto, antes da construção de um modelo, os dados em duas partes: um conjunto de treinamento e um conjunto de testes.

Usando a matriz de rótulos de classe verdadeira, podemos avaliar a precisão dos valores previstos do nosso modelo comparando as duas matrizes (test_labels vs. preds). Utilizaremos a função accuracy_score() do sklearn para determinar a precisão do nosso classificador de machine learning.
