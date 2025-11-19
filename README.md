# RocketLabDadosDesafio3 - Camada Gold e Orquestração

Este repositório contém a etapa final do desafio de Engenharia de Dados (Arquitetura Medalhão), focado na Camada Gold e na Orquestração dos Jobs.

Nota Importante: A primeira parte deste projeto (Ingestão/Bronze e Tratamento/Silver) encontra-se no repositório abaixo:

[Acesse a Parte 1 (Bronze e Silver) aqui](https://github.com/analuisafeitosa/RocketLabDadosDesafio2)

## Arquivos neste Repositório

goldlayer.ipynb: Notebook da Camada Gold. Cria as tabelas fatos, dimensões e as views analíticas para as áreas de Logística e Comercial.

job_orquestracao.yaml: Arquivo de configuração do Workflow (Job) que conecta os notebooks Bronze (do outro repo) e Silver com este Gold.

sucesso_job.png: Imagem comprovando a execução bem-sucedida do pipeline completo.

## Tecnologias Utilizadas

Databricks

PySpark & Spark SQL

Orquestração

O pipeline foi orquestrado via Databricks Workflows para execução diária às 13:00, integrando os notebooks dos dois repositórios.

### Imagens da orquestração

<img width="1600" height="820" alt="image" src="https://github.com/user-attachments/assets/f50451ef-b62b-46dc-b076-2111208f5cd1" />
<img width="1218" height="331" alt="image" src="https://github.com/user-attachments/assets/e3994128-8ce7-48f5-8673-8b64c5a741e1" />

