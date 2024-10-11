# Modelo Preditivo de Score de Crédito

Este projeto tem como objetivo desenvolver um modelo preditivo utilizando técnicas de **machine learning** para classificar o score de crédito dos clientes de um banco. Através da análise de dados financeiros e afins, o modelo categoriza os clientes em três grupos de risco de crédito: **Ruim**, **Ok** e **Bom**.

## Tecnologias Utilizadas

- **Python**
- **Pandas**: Para manipulação e análise de dados.
- **scikit-learn**: Para a implementação de algoritmos de machine learning.

## Algoritmos Utilizados

Este projeto realiza a comparação entre dois algoritmos de machine learning:

1. **Árvore de Decisão**: Um modelo interpretável que utiliza uma estrutura de árvore para fazer previsões.
2. **KNN (K-Nearest Neighbors)**: Um modelo baseado na proximidade entre os pontos de dados.

## Funcionalidades

- **Leitura e Preprocessamento de Dados**: Importa um arquivo CSV.
- **Codificação de Variáveis**: Converte variáveis categóricas em numéricas para processamento pelos modelos.
- **Divisão de Dados**: Separa os dados em conjuntos de treino e teste.
- **Treinamento de Modelos**: Treina os modelos de Árvore de Decisão e KNN.
- **Avaliação de Modelos**: Compara a acurácia de ambos os modelos na previsão do score de crédito.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu_usuario/nome_do_repositorio.git
   cd nome_do_repositorio
