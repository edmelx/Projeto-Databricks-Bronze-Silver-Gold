# Projeto-Databricks-Bronze-Silver-Gold
Esse projeto simula a montagem de um pipeline de dados estratégicos

Criei a camada bronze, com dados brutos com erros, duplicatas, incompletos.
Na camada silver, realizei o tratamento e a padronização dos dados, retirando nulos, dados duplicados e corrigindo os tipos de dados.
Na camada gold, mostrei os dados limpos, para calcular KPIs, deixando pronto para leitura e uso.

Também fiz um dashboard de faturamento por região e por produto.

Esse projeto utilizou Databricks, PySpark, Claude e o conceito medallion, o ato de refinamento.

Esse projeto também visa demonstrar que posso trabalhar com Databricks usando o apoio de terceiros, seguindo regras e métodos claros para a execução de projetos. Ainda estou estudando Dados e SQL.

 Camada Bronze (Ingestão): Armazenamento dos dados brutos, preservando a fonte original com todas as suas inconsistências (nulos e duplicatas).
 Camada Silver (Tratamento): Limpeza completa utilizando PySpark para remoção de duplicatas, tratamento de valores nulos, correção de tipos de dados e criação de colunas derivadas (como Região e Mês).
 Camada Gold (Business): Agregação dos dados para cálculo de KPIs estratégicos, como faturamento por categoria e ticket médio.
 Visualização: Criação de um dashboard interativo para análise de faturamento por região e produto.

 https://dbc-73c051ab-4cc4.cloud.databricks.com/dashboardsv3/01f1245e169112408cc5b104d17f619c/published?o=7474656016635469
 link da dashboard
