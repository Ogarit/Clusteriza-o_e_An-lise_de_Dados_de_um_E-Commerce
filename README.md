# Clusterização e Análise de Dados

Este projeto demonstra o uso de técnicas de clusterização para análise de dados, incluindo os algoritmos K-Means e DBSCAN. O notebook abrange desde a etapa de pré-processamento dos dados até a avaliação dos modelos usando métricas e ferramentas de visualização.

## Funcionalidades
- Pré-processamento e normalização dos dados com `pandas` e `sklearn`
- Análise exploratória visual com `matplotlib`, `seaborn` e `plotly`
- Clusterização utilizando `K-Means` e `DBSCAN`
- Avaliação dos clusters com métricas: Silhouette Score, Calinski-Harabasz Score e Davies-Bouldin Score
- Visualização do número ideal de clusters com `yellowbrick`

## Bibliotecas Utilizadas
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`
- `yellowbrick`

## Como Usar
1. Clone o repositório:
   ```bash
   git clone https://github.com/Ogarit/Clusteriza-o_e_Analise_de_Dados_de_um_E-Commerce.git
   ```
2. Descompacte o `data.rar` utilizando o WinRAR ou outro software semelhante.
3. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn yellowbrick
   ```
4. Abra o Jupyter notebook para rodar a análise:
   ```bash
   jupyter notebook cluster.ipynb
   ```

# jupyter notebook cluster.ipynb
- `desafio_7.ipynb`: Notebook principal contendo a análise de clusterização.
- `data.rar`: Dados utilizados compactados.

# Dados
Dados obtidos no Kagle: https://www.kaggle.com/datasets/carrie1/ecommerce-data.

- InvoiceNo: Identificação da transação
- StockCode: Código de estoque do produto
- Description: Descrição do produto
- Quantity: Quantidade de produtos por transação
- InvoiceDate: Data da transação
- UnitPrice: Preço unitário do produto
- CustomerID: Identificação do cliente
- Country: País de origem da transação
