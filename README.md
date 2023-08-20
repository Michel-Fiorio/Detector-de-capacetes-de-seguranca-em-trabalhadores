# Detector-de-capacetes-de-seguranca-em-trabalhadores
Sistema de visão computacional para detecção de capacete de segurança em trabalhadores em canteiros de obras.

Implementação de uma solução de visão computacional que utiliza uma câmera embutida a um notebook e um modelo de IA pré-treinado 
para identificar o uso de capacetes de segurança por trabalhadores em canteiros de obras.

O modelo de IA utilizado é uma rede neural convolucional que foi treinada utilizando um banco de dados de 16867 imagens e possui precisão de 95,1%.

O algoritmo escrito em Python capta a imagem da câmera do notebook, aplica a imagem ao modelo de detecção de objetos e retorna, em tempo real, 
o desenho de caixas delimitadoras ao redor dos rostos das pessoas na imagem. 

São aplicadas corres distintas para as caixas de acordo com a classificação feita pelo modelo.
