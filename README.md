# Highlight of car licenses project
Repositório destinado para implementação de projeto avaliativo do curso de processamento de imagens digitais.

Referência original: https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e

## Objetivos Gerais do Projeto
- Levando em consideração que o projeto original baseia-se na detecção de placas através de técnicas de visão computacional, o mesmo não poderá ser reproduzido nesse projeto visto que há temas que não foram abordados em sala de aula, então o escopo do projeto a ser desenvolvido nesse notebook destina-se a uma implementação bem mais simples e rigorosa com os conteúdos abordados em sala de aula.

- O projeto a ser desenvolvido, sobre a base de imagens do projeto mencionado acima, que apresenta um conjunto de imagens de carros, tem como objetivo o destaque das regiões da imagem que representam as placas dos carros.

- A princípio, tenho como objetivo explorar as técnicas de filtro para melhorar a visibilidade da imagem e realçar áreas de interesse, utilizar técnicas de thresholding para tornar a imagem binária e por fim utilizar técnicas de segmentação de imagens como as transformadas de hough para identificar as retas na imagem, o que acredito que irá facilitar a detecção de formas de interesse na imagem, o que nesse caso são as placas dos veículos, além disso também tenho como objetivo tentar implementar as transformações geométricas para tentar deixar sempre a imagem o mais horizontal possível.