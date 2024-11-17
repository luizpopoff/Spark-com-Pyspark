# Spark-com-Pyspark

# SparkMovies

Este projeto usa PySpark para realizar análises exploratórias em um dataset de filmes, o `movies.csv`. O objetivo principal é entender o funcionamento do Pyspark, extraindo insights sobre o conjunto de dados, incluindo a classificação média dos filmes, a contagem de avaliações e outras métricas de interesse.

## Configuração Inicial

Para configurar o ambiente PySpark, é necessário instalar algumas dependências. O início do notebook fornece instruções detalhadas para:

1. **Instalar o Java**: PySpark requer uma instalação do Java Development Kit (JDK). Certifique-se de instalar o Java 8 ou superior, que pode ser obtido a partir do site oficial [Java SE Development Kit](https://www.oracle.com/java/technologies/javase-downloads.html).
   
2. **Baixar e configurar o Spark**: O Spark também precisa ser baixado e configurado. O notebook orienta o download da versão mais recente do Apache Spark a partir do [site oficial](https://spark.apache.org/downloads.html). Após o download, o Spark deve ser extraído e configurado no sistema.

3. **Configuração das variáveis de ambiente**: Para garantir que PySpark funcione corretamente, é necessário definir as variáveis de ambiente `SPARK_HOME` e `JAVA_HOME`. O notebook fornece um exemplo de como configurar essas variáveis de acordo com o caminho de instalação do Spark e do Java no sistema.

4. **Instalação de outras dependências**: Além disso, o notebook também cobre a instalação de pacotes Python essenciais, como `pyspark` e bibliotecas de visualização de dados.

## Estrutura do Dataset

O dataset `movies.csv` contém as seguintes colunas:

- **Film**: Nome do filme
- **Genre**: Gênero do filme
- **Lead Studio**: Estúdio principal responsável pelo filme
- **Audience score %**: Pontuação do público em porcentagem
- **Profitability**: Lucratividade do filme
- **Rotten Tomatoes %**: Percentual de aprovação no Rotten Tomatoes
- **Worldwide Gross**: Receita mundial do filme
- **Year**: Ano de lançamento

## Funcionalidades

O notebook executa várias tarefas usando PySpark, incluindo:

1. Carregamento do dataset e criação de um DataFrame Spark.
2. Limpeza e transformação dos dados.
3. Cálculo de estatísticas, como média da pontuação de audiência e lucratividade média por gênero.
4. Geração de visualizações para explorar insights dos dados.

## Requisitos

- **Python 3.6+**
- **Java 8+**
- **PySpark**
- **Jupyter Notebook** (opcional, para execução local do notebook)

Para instalar o PySpark, use:

```bash
pip install pyspark
