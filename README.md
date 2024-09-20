# Projeto CarDekho - Previsão de Preço de Carros

## Tecnologias
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)


## Descrição:
Este projeto tem como objetivo criar um modelo preditivo utilizando dados de vendas de automóveis na Índia, fornecidos pelo [Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/car-details-dataset). O modelo será treinado para prever o preço de venda de carros com base em várias características dos veículos.

## Objetivo:
Desenvolver um modelo de regressão para prever o preço de venda de carros usados, maximizando a precisão das previsões.

## Dicionário de Dados:
- **name**: Nome do modelo do carro.
- **year**: Ano de fabricação do carro.
- **selling_price**: Preço de venda do carro.
- **km_driven**: Quilometragem do veículo.
- **fuel**: Tipo de combustível utilizado (ex: gasolina, diesel).
- **seller_type**: Tipo de vendedor (particular ou profissional).
- **transmission**: Tipo de transmissão do veículo (manual ou automática).
- **owner**: Número de proprietários anteriores.

## Bibliotecas Utilizadas:
- **pandas**: Para manipulação de dados.
- **seaborn**: Para visualização de dados.
- **matplotlib**: Para criação de gráficos.
- **numpy**: Para operações matemáticas.
- **Jupyter lab**: Para a codificação.

Você pode instalar todas dependências necessárias com o seguinte comando:

```bash
pip install -r requirements.txt
```

## Etapas do Projeto:
1. **Carregamento dos Dados**: O conjunto de dados foi importado e inspecionado.
2. **Análise Exploratória**: Estatísticas descritivas e visualizações foram utilizadas para entender as principais características dos dados.
3. **Criação do Modelo**: Um modelo de regressão foi treinado para prever o preço de venda dos carros.
4. **Avaliação do Modelo**: O modelo foi avaliado com base em métricas de desempenho para medir sua precisão.

## Como Executar:
1. Clone o repositório.
```bash
git clone https://github.com/Gustavo2022003/CarDekho.git
```
2. Certifique-se de ter as dependências instaladas:
```bash
pip install -r requirements.txt
```
3. Execute o Jupyter Notebook: Abra o arquivo main.ipynb em um ambiente Jupyter:
```bash
jupyter lab main.ipynb
```

