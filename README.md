# 🪙 Crypto Analytics: Análise de Volatilidade em Tempo Real

> **Status:** Concluído ✅

## 📋 Sobre o Projeto
Este projeto desenvolve uma pipeline de dados automatizada que consome informações financeiras de criptomoedas em tempo real, processa os dados para calcular indicadores de volatilidade e gera visualizações para auxiliar na tomada de decisões de investimento.

O objetivo foi aplicar conhecimentos de **Python para Dados** simulando um cenário real de mercado financeiro.

## 🛠 Tecnologias Utilizadas
* **Python 3.x**
* **Pandas:** Manipulação e limpeza de dados (DataFrames).
* **Requests:** Consumo de API REST (CoinGecko/Binance).
* **Seaborn/Matplotlib:** Visualização de dados estatísticos.
* **Jupyter Notebook:** Ambiente de desenvolvimento e análise.

## 📊 Funcionalidades
1.  **Extração de Dados:** Conexão via API para buscar cotações de Bitcoin, Ethereum, Solana, etc.
2.  **Transformação (ETL):**
    * Limpeza de tipos de dados.
    * Cálculo automático da **variação percentual (24h)**.
    * Cálculo de volatilidade (Diferença entre Máxima e Mínima).
3.  **Visualização:** Gráficos de barras comparativos para identificar as moedas mais voláteis do dia.
4.  **Exportação:** Salvamento automático dos dados tratados em `CSV` para histórico.

## 📈 Exemplo de Insights
*(Se possível, adicione um print de um gráfico aqui)*
* O script identifica automaticamente qual moeda teve a maior alta ("Foguete do dia 🚀") e qual teve a maior queda.
* Analisa a correlação entre volume de transações e variação de preço.

## 🚀 Como Executar
1.  Clone este repositório.
2.  Instale as dependências:
    ```bash
    pip install pandas seaborn requests
    ```
3.  Execute o arquivo `KarineOliveira_ProjetoAPI.ipynb` no Jupyter Notebook ou VS Code.

---
**Desenvolvido por [Karine de Oliveira](https://www.linkedin.com/in/karine-oliveira154/)**
