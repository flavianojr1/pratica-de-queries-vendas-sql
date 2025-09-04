# Estudos Introdutórios de SQL - EBAC

Este notebook contém os estudos introdutórios de SQL realizados por **Flaviano Astolfo Junior** como parte do módulo 24 do curso da EBAC, focado em Bancos de Dados e SQL.

## Conteúdo do Notebook

O notebook aborda os seguintes tópicos:

- Preparação do ambiente para trabalhar com SQL Lite e Pandas.
- Carregamento de dados de um arquivo CSV (`TB_VENDAS_TAREFA.csv`) em um DataFrame Pandas.
- Conexão com um banco de dados SQLite em memória e carregamento do DataFrame para uma tabela chamada `tb_vendas`.
- Definição de uma função auxiliar para executar consultas SQL e retornar os resultados como um DataFrame Pandas.
- Resolução de exercícios práticos de SQL, incluindo:
    - Seleção de todos os dados de uma tabela.
    - Seleção de um número limitado de linhas de uma coluna específica.
    - Cálculo da média de colunas numéricas e renomeamento das colunas de resultado.
    - Cálculo do valor total por compra (multiplicando valor unitário por unidades) e exibição das colunas `ID_COMPRA`, `ID_CLIENTE` e o valor total.
    - Cálculo da média do valor total gasto em todas as compras.
- Reflexões pessoais sobre a utilidade do SQL e Python para ciência de dados.
- Diferenciação entre bancos de dados relacionais e não relacionais.
- Opinião sobre a praticidade do SQL para consultas rápidas em comparação com Python.

## Como executar o notebook

Para executar este notebook, você precisará ter o Python instalado e as bibliotecas `sqlite3` e `pandas`. O arquivo `TB_VENDAS_TAREFA.csv` também deve estar no mesmo diretório do notebook ou em um caminho especificado.

1. Execute as células de código sequencialmente.
2. As consultas SQL são executadas através da função `run_query`, que retorna os resultados em um DataFrame Pandas.

Este notebook serve como um registro prático dos conceitos iniciais de SQL e sua aplicação em conjunto com Python para manipulação e análise de dados.
