Projeto de Análise de Dados de Filmes
Este projeto tem como objetivo analisar um conjunto de dados de filmes, contendo informações sobre filmes, avaliações, tags e links para bases de dados externas. O dataset foi obtido do MovieLens, que é uma plataforma de recomendação de filmes.

Descrição do Dataset
O dataset contém dados de filmes, avaliações e tags coletados entre 29 de março de 1996 e 24 de setembro de 2018. Ele inclui:

100.836 avaliações de filmes, com notas de 1 a 5 estrelas.

3.683 tags atribuídas por usuários.

610 usuários que contribuíram com avaliações e tags.

O dataset é composto por quatro arquivos principais:

movies.csv: Contém informações sobre os filmes, incluindo ID do filme, título e gêneros.

links.csv: Contém links para IDs externos, como IMDb e TMDB.

ratings.csv: Contém as avaliações dos usuários, incluindo ID do usuário, ID do filme, avaliação e timestamp.

tags.csv: Contém as tags atribuídas pelos usuários, incluindo ID do usuário, ID do filme, tag e timestamp.

Identificação de Problemas
Colunas com nomes não explícitos: A coluna tmdbId no arquivo links.csv foi renomeada para DatabaseMovieid para melhorar a clareza.

Linhas vazias: Foram removidas as linhas vazias na coluna DatabaseMovieid do arquivo links.csv.

Correção de Imperfeições
Renomeação de colunas: A coluna tmdbId foi renomeada para DatabaseMovieid para facilitar a identificação.

Remoção de linhas vazias: As linhas com valores ausentes na coluna DatabaseMovieid foram removidas para garantir a integridade dos dados.
