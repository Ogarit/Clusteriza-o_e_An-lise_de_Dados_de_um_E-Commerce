# Clusteriza-o_e_Analise_de_Dados_de_um_E-Commerce

Este projeto demonstra o uso de técnicas de **clusterização** para análise de dados de um e-commerce, utilizando algoritmos como **K-Means** e **DBSCAN**. O objetivo é aplicar métodos de pré-processamento e avaliação de modelos, bem como visualizar os resultados obtidos a partir da análise de dados de transações de clientes.

## Funcionalidades

- **Pré-processamento e normalização dos dados** utilizando `pandas` e `sklearn`
- **Análise exploratória de dados** com visualizações interativas utilizando `matplotlib`, `seaborn` e `plotly`
- **Clusterização** com os algoritmos `K-Means` e `DBSCAN`
- **Avaliação de clusters** com métricas: 
  - Silhouette Score
  - Calinski-Harabasz Score
  - Davies-Bouldin Score
- **Visualização do número ideal de clusters** com a ferramenta `yellowbrick`

## Bibliotecas Utilizadas

- `pandas` – Manipulação de dados
- `numpy` – Operações matemáticas e numéricas
- `matplotlib` – Visualizações básicas
- `seaborn` – Visualizações avançadas
- `plotly` – Visualizações interativas
- `scikit-learn` – Algoritmos de machine learning
- `yellowbrick` – Visualização do número ideal de clusters

## Como Usar

### Passos Iniciais

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Ogarit/Clusteriza-o_e_Analise_de_Dados_de_um_E-Commerce.git
2. **Descompacte o arquivo de dados**: O arquivo `data.rar` contém os dados necessários para a análise. Use o WinRAR ou outro software para descompactá-lo.
3. **Instale as dependências necessárias**: Instale as bibliotecas necessárias utilizando o pip:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn yellowbrick
4. **Abra o Jupyter Notebook**: Após instalar as dependências, abra o notebook para rodar a análise:
   ```bash
   jupyter notebook cluster.ipynb

## Estrutura do Projeto

- `cluster.ipynb`: O notebook principal que contém a análise de clusterização, incluindo o pré-processamento dos dados, a aplicação dos algoritmos e as visualizações.
- `data.rar`: Arquivo compactado contendo os dados do e-commerce.

## Dados

Os dados utilizados neste projeto foram obtidos a partir de um conjunto disponível no [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data). O arquivo contém informações de transações realizadas em uma loja online, com as seguintes colunas:
- **InvoiceNo**: Identificação da transação
- **StockCode**: Código de estoque do produto
- **Description**: Descrição do produto
- **Quantity**: Quantidade de produtos vendidos por transação
- **InvoiceDate**: Data da transação
- **UnitPrice**: Preço unitário do produto
- **CustomerID**: Identificação do cliente
- **Country**: País de origem da transação
