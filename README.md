# Trabalho IA 1 – HGTEncoder + Transformer

## Requisitos

Baixe os seguintes arquivos do conjunto de dados IBM AML:

- `LI_Small_accounts.csv`
- `LI_Small_Trans.csv`

Dataset disponível em:
https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml

## Preparação

1. Baixe este repositório em formato `.zip`.
2. Extraia os arquivos do projeto.
3. Coloque os seguintes arquivos no mesmo diretório (ou ajuste os caminhos conforme necessário):
   - `LI_Small_accounts.csv`
   - `LI_Small_Trans.csv`
   - Arquivo `00`
   - Arquivo `01`

## Execução

### 1. Pré-processamento

Execute o arquivo **00** completamente.

Antes da execução, altere as seguintes variáveis para apontarem para os caminhos corretos dos arquivos:

- `caminho`
- `caminho_accounts`
- `caminho_trans`

Essas variáveis devem referenciar os arquivos:

- `LI_Small_accounts.csv`
- `LI_Small_Trans.csv`

### 2. Modelagem

Após a conclusão do arquivo **00**, execute o arquivo **01**.

Este arquivo realiza:

- Construção do grafo heterogêneo;
- Modelagem utilizando o **HGTEncoder**;
- Treinamento do modelo;
- Avaliação dos resultados e métricas de desempenho.

## Ordem de execução

1. Baixar o dataset.
2. Configurar os caminhos dos arquivos.
3. Executar o arquivo **00**.
4. Executar o arquivo **01**.
