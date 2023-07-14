# **Germany Used Cars - Modelo Preditivo**

O mercado de automóveis nas últimas décadas se desenvolveu para um mercado com uma variedade imensa de modelos, marcas e categorias, com os mais diversos propósitos. Além disso, ainda há a atualiação de linhas de carros, com novos desingns e tecnologias. Para haver tantas opções que um consumidor pode escolher, também há demanda para isso. 

Nesse contexto, surgem mercados com propostas semelhantes, como marketplaces e mercados de carros usados. No entanto precificar um carro usado, ou carro novo que é vendido ao lado de um carro usado, não é uma tarefa simples, pois haverá diversos fatores que influenciaram o preço do carro, inclusive a forma como ele foi utilizado anteriormente, e o seu estado em relação a um modelo 0 quilômetro. Ou seja, conseguir prever o preço esperado de um carro dado alguns de seus atributos e estado pode ser de grande valor para um mercado de carros usados, ou até mesmo marketplaces.

Para realização de tal tarefa será utilizado um dataset com informações referentes ao AutoScout24, um dos maiores marketplaces de venda de carros da Alemanha.

## **Objetivo**

Construção de um modelo preditivo para os preços do automóveis.

Não será utilizado um threshold para as métricas de performance, pois não foi houve qualquer contato prévio com os dados. Será selecionado o melhor algoritmo encontrado, posteriormente será realizada uma tentativa de calibração de hiperâmetros a esse algoritmo, caso possível.

## **Pré-requisitos**

Para realização dessa atividade será utilizado apenas Python 3.11.3 com as seguintes bibliotecas e versões:

seaborn          : 0.12.2
pandas           : 2.0.3
re               : 2.2.1
scipy            : 1.11.1
category_encoders: 2.6.1
numpy            : 1.24.4
matplotlib       : 3.7.1


## **Dados utilizados**

Segundo a [fonte de dados](https://www.kaggle.com/datasets/wspirat/germany-used-cars-dataset-2023), os dados foram obtidos por meio de um scrap de dados, que abrange carros fabricados de 1995 até 2023. É necessário uma conta no site para realizar o Download dos arquivos. O único pré-requisito é manter o arquivo arquivo na mesma pasta em que o arquivo jupyter-notebook está.

Além disso, o dataset possui, originalmente, 15 colunas contendo informações como marca, modelo, cor, potência, consumo e preço.

## **Licença**

Os dados utilizados possuem a licença CC0 de dominio público e foram disponibilizados por wspirat em [Kaggle](https://www.kaggle.com/datasets/wspirat/germany-used-cars-dataset-2023) e tratam de informações sobre carros da [Autoscout24](https://www.autoscout24.de/).

**[Germany Used Cars Dataset 2023](https://www.kaggle.com/datasets/wspirat/germany-used-cars-dataset-2023) by wspirat. The data is dedicated to the public domain under CC0.**

