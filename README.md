# portfolio
Análise de Vendas de Exportação

Este projeto de análise de dados explora o desempenho de vendas de exportação de uma empresa fictícia, com o objetivo de identificar tendências, os produtos mais vendidos e os mercados mais importantes. A análise foi desenvolvida em um Jupyter Notebook, utilizando bibliotecas populares de Python para manipulação, análise e visualização de dados.

Visão Geral do Projeto

A análise segue um fluxo de trabalho típico de ciência de dados, que inclui:

    Limpeza e Pré-processamento de Dados: Verificação de valores ausentes, correção de tipos de dados e organização do conjunto de dados para análise.

    Análise Exploratória de Dados (EDA): Entendimento da distribuição dos dados e identificação das principais métricas de desempenho.

    Análise de Vendas por Período: Acompanhamento da evolução das vendas ao longo do tempo (por ano e mês) para detectar sazonalidade ou tendências.

    Identificação de Mercados e Produtos-Chave: Análise de vendas por país e por categoria de produto para destacar os maiores contribuintes para a receita.

Tecnologias e Bibliotecas

O projeto foi construído usando as seguintes ferramentas:

    Python 3

    Pandas: Para manipulação e análise de dados.

    Matplotlib: Para a criação de gráficos e visualizações.

    Seaborn: Para visualizações estatísticas mais aprimoradas.

Conjunto de Dados

O projeto utiliza o arquivo ExportSales.csv, que contém informações sobre as vendas de exportação. As colunas incluem:

    ID: Identificador único da transação.

    Date: Data da venda.

    Category: Categoria do produto.

    Invoice Number: Número da fatura.

    Product Code: Código do produto.

    Customer Code: Código do cliente.

    Destenation: País de destino (código de 3 letras).

    QTY: Quantidade vendida.

    Total Price: Preço total da venda.

Principais Conclusões

A análise resultou nos seguintes insights:

    As vendas totais e a quantidade de produtos vendidos demonstraram um crescimento significativo ao longo dos anos.

    O país IRQ foi identificado como o principal mercado de exportação, gerando o maior volume de vendas.

    A Categoria 5 se destacou como a de maior receita, seguida de perto pelas Categorias 1 e 8.

Como Executar o Projeto

Para replicar a análise, siga os passos abaixo:

    Certifique-se de ter o Python instalado.

    Instale as bibliotecas necessárias com o seguinte comando:
    Bash

    pip install pandas matplotlib seaborn

    Faça o download dos arquivos ExportSales.ipynb e ExportSales.csv.

    Abra o Jupyter Notebook ou JupyterLab e execute todas as células do notebook.

Você pode explorar e modificar o código para realizar suas próprias análises ou criar novas visualizações.

