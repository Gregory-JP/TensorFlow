# TensorFlow

O Tensorflow é uma das bibliotecas mais amplamente utilizadas para implementar o aprendizado de máquina e outros algoritmos que envolvem grandes operações matemáticas. O Tensorflow foi desenvolvido pelo Google e é uma das bibliotecas de aprendizado de máquina mais populares no GitHub. O Google usa o Tensorflow para aprendizado de máquina em quase todos os aplicativos. Se você já usou o Google Photos ou o Google Voice Search, então já utlizou uma aplicação criada com a ajuda do TensorFlow. Vamos compreender os detalhes por trás do TensorFlow.

Matematicamente, um tensor é um vetor N-dimensional, significando que um tensor pode ser usado para representar conjuntos de dados N-dimensionais. Aqui está um exemplo:

<img src='https://user-images.githubusercontent.com/63425849/166586304-fbb2eb40-d8bd-41b2-93fb-11c51ac36484.png' width=400, height=300></img>

A figura acima mostra alguns tensores simplificados com dimensões mínimas. À medida que a dimensão continua crescendo, os dados se tornam mais e mais complexos. Por exemplo, se pegarmos um Tensor da forma (3x3), posso chamá-lo de matriz de 3 linhas e colunas. Se eu selecionar outro Tensor de forma (1000x3x3), posso chamá-lo como tensor ou conjunto de 1000 matrizes 3x3. Aqui chamamos (1000x3x3) como a forma ou dimensão do tensor resultante. Os tensores podem ser constantes ou variáveis.

## TensorFlow vs Numpy
TensorFlow e NumPy são bastante semelhantes (ambos são bibliotecas de matriz N-d). NumPy é o pacote fundamental para computação científica com Python. Ele contém um poderoso objeto array N-dimensional, funções sofisticadas (broadcasting) e etc. Acredito que os usuários Python não podem viver sem o NumPy. O NumPy tem suporte a matriz N-d, mas não oferece métodos para criar funções de tensor e automaticamente computar derivadas, além de não ter suporte a GPU, e esta é uma das principais razões para a existência do TensorFlow. Abaixo uma comparação entre NumPy e TensorFlow, e você vai perceber que muitas palavras-chave são semelhantes.

## Usando Variáveis
O TensorFlow também possui nodes variáveis que podem conter dados variáveis. Elas são usados principalmente para manter e atualizar parâmetros de um modelo de treinamento. Variáveis são buffers na memória contendo tensores. Elas devem ser inicializados e podem ser salvas durante e após o treinamento. Você pode restaurar os valores salvos posteriormente para exercitar ou analisar o modelo. Uma diferença importante a notar entre uma constante e uma variável é:
O valor de uma constante é armazenado no grafo e seu valor é replicado onde o grafo é carregado. Uma variável é armazenada separadamente e pode estar em um servidor de parâmetros.

Site oficial do TensorFlow: https://www.tensorflow.org/
