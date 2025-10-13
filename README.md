# Pipeline de Análise de Dados Financeiros

## Título e Descrição do Projeto

Este projeto implementa um pipeline completo de análise financeira, automatizando desde a coleta de dados até a visualização de resultados.
O sistema realiza a extração de dados históricos de diferentes ativos (como NASDAQ, Ibovespa e Bitcoin), aplica transformações e cálculos estatísticos (retornos diários, volatilidade, médias móveis, etc.), armazena os dados processados e gera visualizações interativas que facilitam a interpretação do desempenho do mercado.
O principal objetivo é oferecer um fluxo de trabalho robusto, reprodutível e escalável para exploração e análise de dados financeiros.

## Funcionalidades

*   **Ingestão de Dados:** Coleta dados históricos de preços e volume para ativos selecionados usando a API do Yahoo Finance.
*   **Transformação de Dados:** Limpa os dados brutos, calcula retornos diários e acumulados, volatilidade e médias móveis.
*   **Armazenamento de Dados:** Salva os dados brutos e processados em formatos CSV e Parquet, simulando um Data Lake local.
*   **Visualizações:** Gera gráficos interativos (preços, retornos, volatilidade, volume, médias móveis e candlestick) para análise visual.
*   **Resumo:** Apresenta uma tabela resumo com métricas chave de desempenho para cada ativo.

## Tecnologias Utilizadas

*   **Python:** Linguagem de programação principal.
*   **pandas:** Manipulação e análise de dados.
*   **plotly:** Geração de visualizações interativas.
*   **dash:** (Mencionado no `pip install`, mas não totalmente utilizado para um dashboard completo neste notebook)
*   **yfinance:** Coleta de dados financeiros.
*   **schedule:** (Mencionado no `pip install`, para agendamento futuro)
*   **python-dotenv:** (Mencionado no `pip install`, para variáveis de ambiente futuras)
*   **requests, numpy, datetime, json, os, typing:** Bibliotecas auxiliares.

## Como Configurar

1.  **Clonar o Repositório:** (Se o projeto estiver em um repositório)
