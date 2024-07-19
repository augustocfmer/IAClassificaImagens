# Projeto de Classificação de Dígitos MNIST com TensorFlow

Este projeto demonstra como construir, treinar e avaliar um modelo de rede neural convolucional (CNN) para a classificação de dígitos manuscritos utilizando o dataset MNIST. O projeto é desenvolvido com TensorFlow e Keras.

Requisitos
Python 3.x
TensorFlow
Matplotlib
NumPy

Você pode instalar as dependências usando pip:

pip install tensorflow matplotlib numpy

Estrutura do Projeto
Importação de Bibliotecas: Importamos as bibliotecas necessárias, incluindo TensorFlow, Keras, Matplotlib e NumPy.

Carregamento e Preparação do Dataset: Carregamos o dataset MNIST e normalizamos os pixels das imagens para o intervalo [0, 1]. Adicionamos uma dimensão de canal para as imagens.

Definição da Arquitetura do Modelo: Construímos uma CNN com camadas convolucionais, de pooling, de flattening e densas.

Compilação do Modelo: Compilamos o modelo utilizando o otimizador Adam e a função de perda de entropia cruzada categórica esparsa.

Treinamento do Modelo: Treinamos o modelo com o dataset de treinamento por 5 épocas, validando-o com o dataset de teste.

Avaliação do Modelo: Avaliamos o desempenho do modelo no dataset de teste.

Plotagem de Imagens de Teste e Previsões: Plotamos algumas imagens de teste junto com as previsões do modelo.

Salvar o Modelo: Salvamos o modelo treinado em um arquivo .h5.

