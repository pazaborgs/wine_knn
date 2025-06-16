# Classificação de Vinhos usando KNN 🍷

Este projeto demonstra na prática o uso de um algoritmo de K-Nearest Neighbors (KNN) para classificar diferentes tipos de vinho com base em características químicas. O conjunto de dados utilizado é o famoso Wine Dataset e aborda desde o pré-processamento dos dados até a avaliação dos modelos e visualização final.

![Capa](images/capa.png)

## Objetivo

Demonstrar o uso de KNNs em um problema real de classificação multiclasse, aplicando conceitos como:

- Normalização dos dados.
- Divisão em conjuntos de treino e teste.
- Visualização dos dados com PCA.
- Avaliação da acurácia do modelo.

## Artigo relacionado

Para entender mais sobre o algoritmo KNN, confira o meu artigo completo no LinkedIn:

👉 [Aprendendo sobre o Algoritmo KNN](https://www.linkedin.com/pulse/aprendendo-sobre-o-algoritmo-knn-patrick-regis-lvlde)

## Dataset

O conjunto de dados utilizado é o **Wine Dataset**, disponível via `sklearn.datasets`. Ele contém:

- 178 amostras  
- 13 características (features) químicas como teor de álcool, magnésio, fenóis, etc...
- 3 classes de vinho (target)

---

# Executando o Código

Clone o repositório ou baixe o notebook abaixo:

   ```bash
   git clone https://github.com/pazaborgs/wine_knn
   cd wine_knn
   ```
   
Instale as dependências:

  ```bash
  pip install -r requirements.txt
  ```

Abra o arquivo com Jupyter Notebook ou ferramenta a sua escolha (Colab...):

  ```bash
  jupyter notebook wine_knn.ipynb
  ```


