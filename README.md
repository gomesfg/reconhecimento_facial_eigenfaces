## Reconhecimento Facial Eigenfaces

FURB - Pós Graduação em Data Science
Aprendizado não-supervisionado
Aluno: Felipe Eduardo Gomes<br/>
Repositório dos fontes do Trabalho Final de Aprendizado Não Supervisionado - FURB

### 1) Passo-a-passo

> a) Baixar o arquivo "trabalho_final_aprendizado_não_supervisionado.py"

> b) Baixar o diretório "Fotos"

> c) Baixar arquivo "haarcascade_frontalface_default.xml"

> d) Executar o código através do **[Google Colab](https://colab.research.google.com/)** sendo que o diretório "Fotos" e o arquivo XML, devem ser carregados para o ambiente de execução.

### 2) O Projeto

Este projeto trata-se de um detector e reconhecedor facial utilizando Python e a biblioteca OpenCV. Como método de amostragem, foi utilizado holdout de 70% das imagens para treinamento e 30% para os testes, sendo que o algoritmo sorteia aleatoriamente as imagens de treino e teste. Foram utilizadas 410 imagens de 41 pessoas diferentes para o reconhecimento. O algoritmo realiza o treinamento e o teste utilizando de 10 a 20 componentes principais (PCA) e registra a acurácia (percentual de acerto das imagens) de cada número de componentes diferentes.

- Biblioteca OpenCV

```
import cv2
```

<br/>

- Biblioteca do sistema operacional para manipulação das fotos

```
import os
```

<br/>

- Biblioteca numpy

```
import numpy as np
```

<br/>

- Biblioteca para embaralhar as imagens

```
import random
```

### 3) Resumo da Acurácia

O resultado do algoritmo de reconhecimento facial, é o resumo dos resultados da acurácia do reconhecimento das execuções utilizando desde as 10 componentes principais até as 20 componentes principais. A Acurácia é o total das imagens de teste reconhecidas corretamente pela aplicação, dividido pela quantidade total de imagens de teste, multiplicado por 100. Segue abaixo o resultado final:<br/>
![alt text](resumo_acuracia.PNG 'Title')
