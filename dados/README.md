# Dicionários de dados

## [`poemas_df.csv`](poemas_df.csv)

Resultados da extração dos textos dos arquivos DOCX.

- **Título:** título do poema;
- **Texto:** conteúdo do poema;
- **Estudante:** autor(a) do poema;
- **Série:** ano escolar do ensino fundamental (6, 7, 8 ou 9) ou série do ensino médio (1, 2 ou 3) do(a) autor(a) do poema no momento da produção;
- **Edição:** ano referente à edição da publicação do poema (valor que varia de 2010 a 2019).

## [`stopwords.csv`](stopwords.csv)

Arquivo com linha única, contendo termos considerados _stopwords_ para o contexto da modelagem de tópicos.

## [`topicos.csv`](topicos.csv)

Arquivo com tópicos extraídos e discutidos no trabalho.

- **Tópico:** identificador do tópico;
- **Qtd. de poemas:** quantidade de poemas associados ao tópico;
- **Palavras mais frequentes:** top 10 de palavras mais frequentes nos poemas do tópico;
- **Rótulo atribuído:** tema atribuído após leitura das palavras mais frequentes e de alguns poemas do tópico.
