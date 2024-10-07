# Análise de Variação do Preço da Gasolina

Este projeto realiza uma análise da variação percentual anual do preço médio da gasolina comum no estado do Rio de Janeiro. O objetivo é compreender como os preços se comportaram ao longo dos anos e fornecer insights sobre essa evolução.

## Dataset

O conjunto de dados utilizado foi obtido no Kaggle, que contém informações sobre os preços dos combustíveis no Brasil, incluindo o preço da gasolina ao longo do tempo em diferentes estados.

- [Link para o dataset no Kaggle](https://www.kaggle.com/datasets/matheusfreitag/gas-prices-in-brazil)

## Estrutura do Projeto

O projeto está estruturado em um notebook Jupyter (`analise_preco_gasolina.ipynb`), que contém as seguintes seções principais:

1. **Objetivo da Análise**:
   - Definição clara do objetivo: gerar uma tabela que mostra a variação percentual ano a ano do preço médio da gasolina no Rio de Janeiro.

2. **Carregamento e Tratamento dos Dados**:
   - Leitura dos dados do arquivo `.tsv` e tratamento de colunas relacionadas a datas e preços.
   - Limpeza e manipulação dos dados para que fiquem prontos para análise.

3. **Cálculo da Variação Percentual**:
   - Processamento dos dados para calcular a variação percentual do preço médio da gasolina ano a ano.

4. **Visualização dos Dados**:
   - Criação de gráficos e tabelas que mostram a evolução dos preços de forma clara e visual.

## Bibliotecas Utilizadas

- `pandas`: Para manipulação e análise de dados.
- `numpy`: Para operações numéricas.
- `matplotlib`: Para criação de gráficos.
- `seaborn`: Para visualizações estatísticas.
