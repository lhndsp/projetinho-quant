# 1. Importação de dataset de preço histórico

Para a importação de dados existem diversas bibliotecas em python que fornem preços históricos de ativos

Dentre elas podemos citar as seguinte plataformas:

- Google Finance [via pandas_datareader](https://pandas-datareader.readthedocs.io/en/latest/)
- Yahoo Finace ([via pandas_datareader](https://pandas-datareader.readthedocs.io/en/latest/) ou [yfinance](https://github.com/ranaroussi/yfinance))
- [Quandl](https://github.com/quandl/quandl-python)
- Investing.com [investpy](https://investpy.readthedocs.io)

Pesquise sobre como importar dados nessas bibliotecas. Os datasets que conseguimos com essas bibliotecas são denominados **OHLCV** *(open-high-low-close-volume)*.

- 1.1) Plote os preços de fechamento
- 1.2) Faça uma simples análise qualitativa do ativo escolhido (Ex: porque ele teve grande variação em algum momento)