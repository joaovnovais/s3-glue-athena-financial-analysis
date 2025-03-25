# Análise de Dados do Preço das Ações da Amazon Utilizando AWS e Python

Este projeto tem como objetivo analisar o preço das ações da Amazon, utilizando dados históricos e ferramentas da AWS, com o processamento dos dados feito em Python. O fluxo de trabalho do projeto inclui a coleta de dados, análise e visualização dos preços das ações da Amazon ao longo do tempo.

## Descrição do Projeto

O projeto foi desenvolvido para praticar habilidades de engenharia de dados, utilizando AWS (como o S3 para armazenamento dos dados) e Python (com bibliotecas como Pandas e Matplotlib para análise e visualização). A análise inclui:

- Carregamento de dados de um arquivo CSV que contém informações sobre o preço das ações da Amazon.
- Processamento dos dados para cálculo de médias móveis (7 e 30 dias) e variação percentual diária do preço de fechamento.
- Geração de gráficos para visualização da evolução do preço das ações ao longo do tempo.

## Como Rodar o Projeto

### Pré-requisitos

1. **AWS S3**: Dados de entrada estão armazenados no Amazon S3.
2. **Google Colab**: Para execução do código Python.
3. **Python**: O código foi escrito em Python, utilizando as bibliotecas:
   - `pandas` para manipulação de dados.
   - `matplotlib` para criação de gráficos.
   - `boto3` para interação com a AWS S3.

