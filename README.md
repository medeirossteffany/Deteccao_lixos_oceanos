# Projeto: Protótipo de Simulação de Análise de Oceanos e Mares por Drone

## Descrição do Projeto

Este projeto é um protótipo de simulação de um drone que analisa oceanos e mares em tempo real, classificando se há lixo na área analisada. Utilizando um modelo de aprendizado de máquina para a classificação, o programa recebe imagens que simulam a captura feita pelo drone e determina se a área está limpa ou suja.

Para simular a localização da análise, o usuário fornece um endereço, e o programa utiliza a API Nominatim do OpenStreetMap para converter o endereço em coordenadas de latitude e longitude. O programa também registra a data e a hora da análise, simulando um sistema de registro em tempo real.

Este projeto foi desenvolvido como parte do Global Solution da faculdade FIAP pelos membros:
- Steffany Medeiros (RM 556262)
- Milena Garcia (RM 555111)
- Gustavo Henrique (RM 556712)

## Funcionalidades

- Carregamento de imagens para análise.
- Classificação das imagens utilizando um modelo pré-treinado para determinar se a área está limpa ou suja.
- Conversão de endereços em coordenadas geográficas (latitude e longitude) usando a API Nominatim.
- Registro da data e hora da análise.
- Armazenamento dos resultados de múltiplas análises para revisão posterior.

## Observações

- Coloque o arquivo keras_model.h5 no diretório do programa.
- Coloque as imagens que deseja analisar no diretório do programa. (Exemplo imagem: marLimpo.jpg) 
- O programa solicitará o caminho da imagem que você deseja analisar. Digite o caminho completo da imagem. (Exemplo caminho pelo colab: marLimpo.jpg) 

## Requisitos

- Python 3.x
- Bibliotecas Python: Keras, Pillow, NumPy, Requests

Você pode instalar as bibliotecas necessárias usando pip:
```bash
pip install keras pillow numpy requests



