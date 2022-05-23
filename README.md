# proj3-fsi
A segmentação de instâncias envolve detectar objetos e segmentação semântica ao mesmo tempo.
O banco de imagens
https://www.kaggle.com/datasets/usmanafzaal/strawberry-disease-detection-dataset

possui 2500 imagens, com anotações correspondentes para sete (7) tipos diferentes de doenças em morango. Um método de segmentação de instância baseado na rede Mask R-CNN foi publicado em
Afzaal, U.; Bhattarai, B.; Pandeya, Y.R.; Lee, J. An Instance Segmentation Model for Strawberry
Diseases Based on Mask R-CNN. Sensors 2021, 21, 6565.

Este projeto pede o seguinte: (utilizando as 2500 imagens e anotações)
Escrever um projeto Keras/TensorFlow, que rode em colab/Google jupyter, e aplique uma rede
YOLACT++, para realizar a segmentação de instâncias dessas imagens e comparar com os
resultados do artigo citado.

Avaliações extras:
1. Métricas mAP IOU 0.5, mAP IOU 0.5: 0.95 em todas as classes;
2. Pequeno relatório/texto indicando resultados de sucesso e potenciais melhorias futuras;
