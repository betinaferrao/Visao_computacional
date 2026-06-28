# Classificação de Doenças Foliares com Aprendizagem de Máquina e Aprendizagem Profunda

## Descrição

Este projeto implementa e compara técnicas de Aprendizagem de Máquina Clássica e Aprendizagem Profunda para a classificação de doenças foliares utilizando imagens do conjunto de dados PlantVillage.

Os modelos implementados foram:

* Mahalanobis
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest
* MobileNetV2 (Transfer Learning)
* ResNet50 (Transfer Learning)

Além da classificação das doenças, o projeto realiza a segmentação das lesões foliares para estimar a severidade da doença. Tal como apresentado na imagem.

<img width="873" height="295" alt="image" src="https://github.com/user-attachments/assets/30b8a894-b6cf-400c-b5d6-95f7441aaec8" />

## Dataset

O conjunto de dados utilizado foi o **PlantVillage**, obtido automaticamente através da biblioteca `kagglehub`.

## Execução

Após instalar as dependências necessárias, execute o arquivo principal do projeto.

Os modelos de Deep Learning são carregados a partir dos arquivos `.keras`. Caso esses arquivos não estejam disponíveis, o código realiza o treinamento e salva os modelos automaticamente.

## Checkpoints da Rede Neural

Os checkpoints (modelos treinados) utilizados neste projeto são:

* `modelo_mobilenetv2.keras`
* `modelo_resnet50.keras`

Os arquivos podem ser acessados no seguinte link:

**Link:**

## Utilização de Inteligência Artificial Generativa

Durante o desenvolvimento deste projeto foi utilizada Inteligência Artificial Generativa como ferramenta de apoio.

**Ferramenta utilizada:**

* ChatGPT (OpenAI)

**Principais utilizações:**

* Auxílio na implementação e organização de trechos do código;
* Esclarecimento de dúvidas sobre TensorFlow, Keras, Scikit-learn e OpenCV;
* Apoio na documentação e comentários do código;
* Auxílio na identificação e correção de erros durante o desenvolvimento.

Todo o código foi revisado, adaptado e testado pelos integrantes do grupo.


## Autores

* Betina Corazza Ferrão
* Jenifer Sofia Ovejero
* Ricardo Bertotto Ribeiro
