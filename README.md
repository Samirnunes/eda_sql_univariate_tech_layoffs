# Análise Univariada em SQL: Layoffs nas Empresas de Tecnologia (2022-2023)

<p align="center">
    <img width="500" src="https://github.com/Samirnunes/eda_sql_univariate_tech_layoffs/blob/main/images/sqlite.jpg" alt="Material Bread logo">
<p>
 
Fonte dos dados: https://www.kaggle.com/datasets/salimwid/technology-company-layoffs-20222023-data

O objetivo deste projeto é utilizar os dados atuais acerca das demissões nas áreas de tecnologia de 
várias empresas para praticar o uso da linguagem SQL (Standard Query Language) para análise de dados.

Escolheu-se realizar apenas uma análise univariada das colunas do conjunto de dados de forma a simplificar
o contexto da análise e focar nas habilidades técnicas envolvendo o banco de dados SQLite e a linguagem SQL, como
preparação dos dados, criação do banco de dados e consultas a esse banco de dados utilizando a biblioteca
sqlite3 do Python em associação à biblioteca Pandas.

## Dados e Descrições

A seguir, encontram-se as primeiras linhas do conjunto de dados:

<p align="center">
    <img width="1000" src="https://github.com/Samirnunes/eda_sql_univariate_tech_layoffs/blob/main/images/visao_geral_dataframe.PNG" alt="Material Bread logo">
<p>

Suas colunas possuem as seguintes descrições:

- ID: chave primária inteira;

- company: empresa que realizou o layoff (demissão em massa);

- total_layoffs: número de funcionários demitidos até janeiro de 2023;

- impacted_workforce_percentage: porcentagem da força de trabalho total da empresa que foi demitida pelos layoffs;

- reported_date: data em que o primeiro layoff ou planos de layoff da empresa foram anunciados;

- industry: segmentos de atuação da empresa;

- headquarter_location: localização da sede da empresa;

- sources: fonte dos dados;

- status: se a empresa é pública ou privada.

- additional_notes: notas adicionais sobre o plano de layoffs da empresa.

## Tecnologias e Bibliotecas Utilizadas

- Jupyter Notebook
- SQL (SQLite)
- Python
- Pandas
- Matplotlib
