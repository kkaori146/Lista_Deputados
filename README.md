# Pesquisa dos Gastos dos Deputados durante o período de 2015 - 2022

<hr/>

## Dados obtidos

### URL da API da Alesp

<hr/>

- URL Despesas:

http://www.al.sp.gov.br/repositorioDados/deputados/despesas_gabinetes.xml


- URL Cadastro:

https://www.al.sp.gov.br/repositorioDados/deputados/deputados.xml

<hr/>

## Etapas

- os dados foram lidos em formato xml e depois convertidos para csv

- tratamento realizado utilizando Pandas, Pandera e Numpy

- plotagem dos dados realizado preliminarmente em Pandas

- o dataset final foi armazenado em um bucket na GCP e posteriormente utilizado para análise no BigQuery

- posteriormente as análises no BigQuery foram utilizadas no Data Studio para a criação de um Dashboard

- o dataset final foi utilizado para a criação de pipelines

<hr/>