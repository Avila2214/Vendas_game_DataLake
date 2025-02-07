## Sobre o Projeto

Este projeto realiza a análise e o processamento de dados sobre vendas de jogos de vídeo game, utilizando uma estrutura de Data Lake para organizar. Com a análise deste conjunto de dados, o objetivo é identificar padrões e tendências de vendas de jogos e gerar insights úteis sobre o comportamento do mercado de jogos.

## Estrutura do Projeto

- **Bronze**: Contém os dados brutos conforme recebidos das fontes originais, sem qualquer transformação.
- **Silver**: Dados parcialmente limpos e organizados, prontos para análises exploratórias.
- **Gold**: Dados totalmente refinados e transformados, prontos para dashboards, relatórios e machine learning.

## Tecnologia Utilizada

- **Linguagem**: Python
- **Biblioteca**: Pandas e Numpy
- 
- **Ferramentas**: Jupyter Notebook - para análise exploratória

## Funcionalidades

- **Extração de dados**: Coleta de dados de preços de combustíveis para diferentes regiões do Brasil.
- **Limpeza e transformação incremental de dados**: Processamento e transformação dos dados para garantir qualidade e consistência.
- **Armazenamento de dados organizados em camadas**: Organiza os dados em camadas (Bronze, Silver e Gold) para facilitar análise e visualização.

## Instruções para Execução

**Clonar o repositório**:
https://github.com/Avila2214/Vendas_game_DataLake.git

**Instale as dependências necessárias.**

**Execute os scripts na ordem para simular o pipeline de ETL**:

scripts python/camada_bronze.py scripts python/camada_prata.py scripts python/camada_ouro.py
