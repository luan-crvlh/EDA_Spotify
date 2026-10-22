# Análise exploratória de músicas do Spotify

Notebook em Python que explora uma base pública de faixas do Spotify para entender o que se relaciona com a popularidade de uma música.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luan-crvlh/EDA_Spotify/blob/main/EDA_Spotify.ipynb)

## O que o projeto faz

O notebook baixa o conjunto [Ultimate Spotify Tracks DB](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db) pelo `kagglehub`, remove linhas incompletas e analisa:

- as 20 faixas mais populares, com e sem filtro;
- a popularidade média;
- a correlação entre atributos numéricos e popularidade nas faixas com nota 80 ou mais;
- a popularidade por gênero e por artista;
- o top 50 da base;
- os gêneros mais comuns e o gênero com maior energia média.

## Principal conclusão

Nenhum atributo numérico analisado mostrou correlação direta com a popularidade. Isso não quer dizer que a popularidade seja aleatória. Ela pode depender de fatores que não estão nessas colunas.

## Por que foi feito

O projeto pratica o fluxo básico de ciência de dados: obter a base, limpar, fazer perguntas, gerar gráficos e tirar conclusões com cuidado. Um resultado negativo, como a falta de correlação, também é um resultado e precisa ser interpretado.

## Como executar

Abra o notebook no Google Colab pelo botão acima e execute as células em ordem. Para rodar localmente:

```bash
pip install kagglehub pandas numpy matplotlib jupyter
jupyter notebook EDA_Spotify.ipynb
```

O download da base pode exigir login no Kaggle.
