# Análise de Câncer de Mama com Machine Learning

![Câncer de Mama](https://storage.googleapis.com/kaggle-datasets-images/180/384/3da2510581f9d3b902307ff8d06fe327/dataset-cover.jpg)

## Descrição do Projeto
Este projeto tem como objetivo analisar um conjunto de dados de diagnóstico de câncer de mama, realizando desde a limpeza e análise exploratória até a aplicação de algoritmos de Machine Learning para classificar os tumores como benignos ou malignos.


## Contexto do Negócio
O diagnóstico precoce do câncer de mama é essencial para aumentar as chances de sucesso no tratamento. Este projeto busca aplicar técnicas de Machine Learning para auxiliar nessa tarefa.

## Dataset
O dataset utilizado neste projeto foi obtido no Kaggle – [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data), que contém dados clínicos derivados de imagens digitalizadas de biópsias de câncer de mama.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para análise de dados e machine learning.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **NumPy**: Biblioteca para operações numéricas.
- **Matplotlib e Seaborn**: Bibliotecas para visualização de dados.
- **Scikit-learn**: Biblioteca para machine learning, utilizada para aplicação do algoritmos de modelagem.

## Metodologia
1. **Carregamento e Exploração dos Dados**: Os dados foram carregados e explorados para entender a estrutura e identificar possíveis valores ausentes ou anomalias.
2. **Pré-processamento**: Realizou-se a limpeza dos dados, normalização, exclusão das variáveis irrelevantes e codificação da variável 'diagnosis'.
3. **Modelagem e Avaliação**: Foram utilizados os seguintes algoritmos para a modelagem dos dados (Naive Bayes, Regressão Logística, KNN, Árvore de Decisão, Random Forest, XGboost, LightGBM e CatBoost), o modelo de XGboost apresentou o melhor desempenho.

   
## Resultados
O modelo XGboost demonstrou excelente desempenho na classificação de imagens de câncer de mama, alcançando uma acurácia de 97,66% e um F1-score de 96,77%. A análise da importância das features revelou que atributos relacionados à forma e tamanho do tumor, como 'radius_mean', 'perimeter_mean', 'area_mean', 'concavity_mean', 'concave points_mean','area_worst', 'concave points_worst', apresentaram os maiores valores de importância, corroborando com estudos da literatura médica que apontam a morfologia tumoral como um dos principais indicadores de malignidade.

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/IsabelleFernanda/breast_cancer_image_analysis
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook em seu ambiente preferido (Jupyter, Google Colab, etc.).

## Contato
**Isabelle Fernanda**  
[LinkedIn](https://www.linkedin.com/in/isabellefernandasilva/) | [GitHub](https://github.com/IsabelleFernanda)  
*Em formação em Ciência de Dados pela EBAC, com experiência em análise de dados, Machine Learning e visualização.*

