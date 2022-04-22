# pln-poemas

## TCC

Disponível no link: http://dspace.sti.ufcg.edu.br:8080/jspui/handle/riufcg/19712

## Sobre o trabalho (Resumo)

O contato com poemas na educação básica é um incentivo para que os alunos descubram o prazer proporcionado pela experiência com a linguagem poética. O Projeto _Coletânea de Poesias_, realizado anualmente no FERA Colégio e Curso, é uma iniciativa que se propõe a promover esse contato através da leitura, apreciação e escrita de poemas, gerando a cada ano um livro com textos redigidos por alunos dos ensinos fundamental e médio. Como a análise desses poemas seria custosa se feita manualmente, o presente trabalho empregou técnicas de Processamento de Linguagem Natural, como _Part-of-Speech tagging_ e modelagem de tópicos, a fim de fazer a mineração dos textos produzidos nas dez edições mais recentes do projeto. Os resultados obtidos reforçam aspectos ligados à liberdade de criação envolvida na produção poética e que os temas abordados pelos alunos variam de acordo com a sua maturidade e o seu ambiente.

## Sobre o repositório

Este repositório concentra os códigos e materiais gerados/utilizados no contexto do Trabalho de Conclusão de Curso em Ciência da Computação intitulado "_Mineração de poemas através de técnicas de Processamento de Linguagem Natural_". Esse trabalho envolveu, dentre outros esforços, técnicas de Processamento de Linguagem Natural como _Part-of-Speech tagging_
e modelagem de tópicos. Nesta última, utilizou-se o algoritmo de _Gibbs Sampling for the Dirichlet Multinomial Mixture_ (GSDMM), com implementação disponível em [repositório _open source_](https://github.com/rwalk/gsdmm/).

### Organização de pastas

Na pasta `/coletaneas`, estão disponíveis os arquivos (em DOCX) contendo os poemas das dez edições mais recentes do _Coletânea de Poesias_. Esses arquivos foram gentilmente cedidos pela equipe organizadora do projeto para os propósitos da pesquisa e, além disso, com permissão de torná-los públicos através deste repositório.

Na pasta `/dados`, encontram-se:

- `topicos.csv`, uma tabela com os tópicos extraídos e discutidos no trabalho;
- `stopwords.csv`, contendo a lista de _stopwords_ considerada durante a análise.

Na pasta `/scripts`, encontram-se os arquivos com os códigos desenvolvidos e utilizados:

- `leitura-docx.ipynb` efetua a extração dos textos dos documentos;
- `pln-poemas.ipynb` é um Python Notebook contendo o passo a passo das análises, com comentários.

Na pasta `/materiais`, encontram-se os materiais adicionais produzidos:

- `score-npmi.pdf`: uma explicação mais detalhada do cálculo de _score_ implementado para modelos de tópicos.
