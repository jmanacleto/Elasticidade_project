# Elasticidade de Preço e Share — Análise de Dados

Este projeto realiza uma análise exploratória e visual da elasticidade de preço em relação ao share de mercado para produtos de consumo. O objetivo é entender como variáveis como preço médio, vendas e índice de preço influenciam o comportamento do consumidor em diferentes regiões.

## 🔍 Objetivos

* Explorar a base de dados de vendas por região, produto e período.
* Identificar correlações entre preço, share e volume de vendas.
* Gerar visualizações que apoiem a compreensão do comportamento do mercado.
* Comparar a distribuição das bases de treino e teste.

## 📁 Estrutura do Projeto

* `main-elasticidade1.ipynb`: Notebook principal com toda a análise de dados e visualizações.
* Arquivos de dados: `base_treino.xlsx` e `base_teste.xlsx` (necessários para execução local).

## 📊 Principais Análises

* Estatísticas descritivas de colunas-chave (preço, vendas, share).
* Boxplots e scatterplots por região para entender variações.
* Matriz de correlação entre variáveis numéricas.
* Análise temporal de variáveis como preço médio e share por produto.
* Comparação entre bases de treino e teste (frequência e cobertura temporal).

## 🛠️ Tecnologias Utilizadas

* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## ▶️ Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale os pacotes necessários:

   ```bash
   pip install pandas matplotlib seaborn openpyxl
   ```

3. Coloque os arquivos `base_treino.xlsx` e `base_teste.xlsx` na raiz do projeto (ou ajuste os caminhos no notebook).

4. Execute o notebook `main-elasticidade1.ipynb` com Jupyter ou VSCode.

## 📈 Exemplos de Visualizações

* Distribuição de vendas por região
* Relação entre preço médio e share com tamanho proporcional às vendas
* Correlação entre variáveis principais
* Comparação da cobertura temporal entre bases

## 📌 Observações

* O notebook ignora avisos de execução para melhor visualização.
* Os nomes de regiões são padronizados para melhor agrupamento.
* As análises são automatizadas com funções modulares para fácil reaproveitamento.
