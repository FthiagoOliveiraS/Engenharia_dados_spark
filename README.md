# ENGENHARIA_DADOS_SPARK
### O projeto a seguir consiste em um pipeline que resgata dados de venda de produtos de 2 filiais diferente e une em uma única base, que servirá como fonte para o time de BI.

# FASES DO PIPELINE
1.   |- Instalação das dependências
2.   |-- Criação da sessão spark
3.   |--- Ingestão dos dados das 2 empresas
4.   |---- Validação dos dados
5.   |----- Data clean
6.   |------ União das bases
7.   |------- Exportação da base em arquivo PARQUET

# REQUISITOS
*   Python 3.13.17
*   Java 1.8.0_461
*   spark 3.1.2
*   Bibliotecas: findspark, pyspark.sql.functions
