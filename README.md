# Análise Exploratória de Dados — Loja Superstore



Projeto desenvolvido para o desafio extra do curso Introdução ao Data Science da SCTEC.



Autora: Laís Kugik Varela Alegri



---



# Objetivo do Projeto



O objetivo deste projeto é realizar uma Análise Exploratória de Dados (AED) utilizando a base de dados pública "Sample Superstore", com foco na compreensão do comportamento das vendas, lucratividade, segmentos de clientes e impacto dos descontos no desempenho comercial da empresa.



A análise foi desenvolvida utilizando Python e bibliotecas voltadas para manipulação, tratamento e visualização de dados.



---



# Dataset Utilizado



Base de dados: Sample Superstore



Fonte:

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final



O dataset contém informações relacionadas a:

- vendas;

- lucro;

- descontos;

- categorias de produtos;

- segmentos de clientes;

- regiões;

- datas de pedidos;

- estados e cidades.



---



# Tecnologias e Bibliotecas Utilizadas



## Linguagem

- Python



## Ambiente de desenvolvimento

- Google Colab



## Bibliotecas utilizadas

- Pandas

- NumPy

- Matplotlib

- Seaborn



## Dashboard

- Looker Studio



---



# Etapas Desenvolvidas



## 1. Importação e compreensão dos dados



Foi realizado o carregamento do dataset em ambiente Python, seguido de uma análise inicial da estrutura dos dados utilizando funções como:

- head()

- info()

- describe()

- shape()



Essa etapa permitiu compreender os tipos de dados e as principais variáveis presentes no conjunto de dados.



---



## 2. Tratamento e preparação dos dados



Durante o tratamento dos dados foram realizadas as seguintes etapas:

- verificação de valores nulos;

- verificação e remoção de registros duplicados;

- conversão de colunas de data;

- criação de colunas auxiliares para análise temporal;

- identificação de possíveis outliers utilizando boxplot e método IQR.



Essas etapas foram importantes para melhorar a qualidade dos dados utilizados nas análises.



---



## 3. Análise Exploratória de Dados (AED)



Foram realizadas análises utilizando filtros, agrupamentos e visualizações gráficas para identificar padrões e gerar insights relevantes.



As principais análises realizadas foram:

- vendas por subcategoria;

- lucro por subcategoria;

- distribuição de vendas por segmento;

- relação entre desconto e lucro;

- evolução das vendas ao longo dos anos;

- top 10 produtos com maior volume de vendas.



---



# Principais Insights Obtidos



- A subcategoria Telefones apresentou destaque no volume de vendas e lucratividade.

- O segmento Consumidor representou a maior participação nas vendas totais.

- Foi identificado que descontos elevados impactam negativamente o lucro em diversas situações.

- A análise temporal demonstrou crescimento das vendas ao longo dos anos analisados.

- Alguns produtos apresentaram desempenho significativamente superior em volume de vendas.



---



# Visualizações Desenvolvidas



O projeto contém diferentes tipos de gráficos para apoiar a interpretação dos dados, incluindo:

- gráficos de barras;

- gráficos de linha;

- gráficos de dispersão;

- gráficos de pizza;

- boxplots.



As visualizações foram utilizadas para facilitar a identificação de padrões e tendências nos dados.



---



# Organização do Projeto



O projeto está organizado nas seguintes estruturas:

- notebook Python (.ipynb);

- dataset em formato .csv;

- gráficos gerados;

- documentação do projeto;

- arquivos complementares.



---



# Como Executar o Projeto



## Requisitos



Instalar as bibliotecas necessárias:



```bash

pip install pandas numpy matplotlib seaborn

```



## Execução



1. Abrir o notebook `.ipynb` no Google Colab; 
   
2. Fazer o upload do arquivo "sample_superstore.csv" na pasta "Arquivos" no Google Colab; 

3. Executar as células em sequência;

4. Visualizar os gráficos e análises geradas.



---



# Dashboard



O dashboard interativo foi desenvolvido utilizando o Looker Studio.



Link do dashboard:

https://datastudio.google.com/reporting/949e2be0-c0b7-4371-a0ed-8bb80e10dad4



---



# Conclusão



A análise exploratória permitiu identificar padrões importantes relacionados ao desempenho comercial da empresa, possibilitando compreender melhor fatores como vendas, lucratividade, segmentos de clientes e impacto dos descontos.

Os resultados obtidos demonstram como técnicas introdutórias de Data Science podem auxiliar na geração de insights relevantes para apoio à tomada de decisão baseada em dados.

