# Explorando IA Generativa com pipeline de ETL com Python
Desafio de código do Bootcamp Santander Ciência de Dados 2023

<br>

Precisei criar meu próprio problema e solução para esse desafio. 

**Contexto:** Você é um cientista de dados de uma companhia aerea e recebeu a tarefa de envolver os clientes de maneira mais personalizada. Seu objetivo é usar o poder da IA Generativa para criar mensagens de recomendação de viagens da companhia personalizadas para cada cliente.

**Condições do Problema:** Você recebeu uma planilha (gerada no [Mockaroo](https://www.mockaroo.com/)) no formato CSV ('[AirlineDataset.csv](/AirlineDataset.csv)'), com dados a respeito dos vôos dos clientes da companhia, e precisa acrescentar a mensagem gerada pela IA a essa planilha para enviar ao setor responsável.

**Resolução:** Utilizei a API da OpenAi, com chat GPT para gerar as mensagens e acrescentei à planilha, gerando a planilha final ['AirlineDatasetUpdated.csv'](/AirlineDatasetUpdated.csv)