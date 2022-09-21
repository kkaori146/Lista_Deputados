# Pesquisa dos Gastos dos Deputados durante o período de 2002 - 2022

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

- o dataset final foi armazenado em um bucket no GCP e posteriormente utilizado para análise no BigQuery

- das análises no BigQuery foi utilizado o Data Studio

- o dataset final foi utilizado para a criação de pipelines

- conversão do dataset final (csv para )

<hr/>

## Descrição das Pastas

- Pasta "BigQuery", arquivo com os principais comandos utilizados no BigQuery;

- Pasta "Colab", arquivo com o google colab principal, onde foi carregado o arquivo xml, conversão e tratamento;

- Pasta "Data Studio", arquivo com o Relatório Breve;

- Pasta "Dataset_Concatenacao_csv", arquivo bruto em formato csv (já concatenado);

- Pasta "Dataset_Concatenado_xml", arquivo bruto em formato xml (já concatenado);

- Pasta "Dataset_Final_csv", arquivo final já tratado

- Pasta "Parquet", arquivos em formato parquet e o google colab utilizado para a conversão;

- Pasta "Pipelines":
-- subpasta "G_Colab_Apache Beam", google colab utilizado para a criação da pipeline;

-- subpasta "Resultados_Dataflow", pipelines criados no Dataflow.