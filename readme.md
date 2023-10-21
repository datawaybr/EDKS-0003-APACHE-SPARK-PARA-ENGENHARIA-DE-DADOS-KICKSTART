# Caminho de Engenharia de Dados com Apache Spark para engenharia de dados kickstart

Bem-vindo ao caminho de engenharia de dados nível Kickstart, onde você aprenderá a usar o Apache Spark para processar dados da Agência Nacional de Aviação Civil (ANAC) do Brasil. Este projeto é destinado a mentoria no campo da engenharia de dados, especificamente focado em como analisar dados no Apache Spark.

> PROJETO TOTALMENTE LOCAL, PRE-Requisitos:
- Docker.
- docker-compose.

### *Todos o notebooks se encontram vazios para que possam acompanhar as aulas e praticar, ao final do projeto sera disponibilizado o repositorio com estes preenchidos.*

# Dados da ANAC
Os dados da ANAC podem ser acessados no seguinte link: https://www.gov.br/anac/pt-br/assuntos/dados-e-estatisticas/historico-de-voos.

# Como Começar
Para começar, siga estas etapas:

1. Clone este repositório em sua máquina local.
2. Execute o docker-compose.yaml para configurar o ambiente de desenvolvimento com PySpark e Jupyter Notebook.

```sh
# primeiramente acesse ao docker compose e identifique o path onde foi realizado o clone do seu repositorio e altere-o ate a pasta app
# se estiver em um ambiente linux basta utilizar o comando PWD
# por fim basta executar o docker-compose e identificar o link de acesso da UI
docker-compose up

#PS: caso o seu docker-compose não rodar execute primeiramente o comando 
docker pull jupyter/pyspark-notebook:spark-3.3.2
```
3. Abra os notebooks na pasta app e siga as instruções para explorar e processar os dados da ANAC.


## Esperamos que você aproveite a mentoria de Apache Spark e a exploração dos dados neste projeto!

# Divirta-se!