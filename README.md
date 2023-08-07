# Word Cloud de Notícias sobre o Twitter no G1

`Vinicius Branco Scortegagna`

<https://www.linkedin.com/in/vinicius-br-sc/>

## Resumo

O objetivo deste trabalho é a obtenção de dados de texto provenientes do site do G1 sobre o Twitter através de Web Mining (Crawling+Scraping) a fim de produzir uma nuvem de palavras (Word Cloud).

Para isso foram utilizadas principalmente as bibliotecas `requests` e `beautifulsoup4` para obter os links e os textos de cada página, bem como `nltk` e `clean-text` para o tratamento dos dados e `matplotlib` com `wordcloud` para a geração da nuvem de palavras.

Uma primeira amostra foi obtida a partir de 47 páginas, seguida de uma segunda com 473.

## Sugestões

Os resultados podem ser refinados adotando-se mais palavras na lista de filtradas (stopwords). Além disso, algo interessante de se observar seria como a nuvem de palavras evoluiu ao longo do tempo, análise esta que já se encontra preparada por terem sido salvas as datas dos textos e links em arquivo `.csv`.
