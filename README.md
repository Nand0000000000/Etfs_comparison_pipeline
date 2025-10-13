# Pipeline de Análise Financeira - Big Data

Este projeto implementa um pipeline simples para coletar, processar, armazenar e visualizar dados financeiros de diferentes ativos (Nasdaq, Ibovespa, Bitcoin) utilizando Python e bibliotecas como `yfinance`, `pandas`, `plotly` e `dash` (embora o dashboard Dash completo não esteja implementado neste notebook, a estrutura para visualização com Plotly está pronta). O pipeline é modular, com classes dedicadas para cada etapa do processo.

## Estrutura do Projeto

O projeto é composto pelas seguintes classes principais:

1.  **`FinancialDataIngestion`**: Responsável pela coleta de dados de fontes externas (atualmente utilizando a biblioteca `yfinance`).
2.  **`FinancialDataTransformation`**: Realiza a limpeza e o enriquecimento dos dados (cálculo de retornos, médias móveis, etc.).
3.  **`FinancialDataStorage`**: Gerencia o armazenamento dos dados brutos e processados em diferentes formatos (CSV, Parquet).
4.  **`FinancialDashboard`**: Contém métodos para gerar visualizações dos dados processados utilizando Plotly.

## Configuração e Instalação

1.  **Clonar o repositório (se aplicável):** Se este código estiver em um repositório, clone-o para sua máquina local ou ambiente de trabalho (como o Google Colab).
