# Análise de Dados com Algoritmo Genético

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Data Analysis](https://img.shields.io/badge/Funcionalidade-Análise%20de%20Dados-brightgreen)
![Python](https://img.shields.io/badge/Linguagem-Python-blue)
![Pandas](https://img.shields.io/badge/Biblioteca-pandas-lightgrey)
![Scikit-learn](https://img.shields.io/badge/Biblioteca-scikit--learn-lightgrey)
![DEAP](https://img.shields.io/badge/Biblioteca-DEAP-lightgrey)
![Matplotlib](https://img.shields.io/badge/Biblioteca-Matplotlib-lightgrey)


Este projeto consiste em um algoritmo genético que realiza uma análise de dados para selecionar os atributos mais relevantes em um conjunto de dados. A seleção de atributos é uma técnica importante na área de aprendizado de máquina e ciência de dados, pois ajuda a melhorar a precisão e a eficiência dos modelos de machine learning.

## Funcionalidade

O código fonte inclui as seguintes funcionalidades:

1. Carregamento dos Dados: O código lê um conjunto de dados a partir de um arquivo CSV.

2. Seleção de Atributos: Utiliza um algoritmo genético para selecionar os atributos mais relevantes do conjunto de dados.

3. Análise de Importância: Calcula a importância de cada atributo usando um modelo Random Forest e exibe os atributos mais importantes em gráficos.

4. Análise de Correlação: Calcula a correlação de Pearson entre os atributos e a variável alvo e exibe os atributos mais correlacionados.

5. Convergência do Algoritmo Genético: Mostra como o algoritmo genético evolui ao longo das gerações por meio de um gráfico.

6. Geração do Melhor Conjunto de Atributos: Após a execução do algoritmo genético, exibe o conjunto de atributos selecionados como resultado.

## Pré-requisitos

Antes de usar o código, certifique-se de que você possui as seguintes bibliotecas Python instaladas:

- pandas
- scikit-learn
- deap
- matplotlib

Você pode instalá-las usando o gerenciador de pacotes `pip`.

## Uso

Para executar o código, siga estas etapas:

1. Clone o repositório.

2. Certifique-se de que os pré-requisitos estão instalados digite pip install -r requirements.txt .

3. Execute o arquivo Notebook do Python `implementação final.ipynb`.

4. Acompanhe a saída do código para ver os resultados da seleção de atributos.



## Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.


