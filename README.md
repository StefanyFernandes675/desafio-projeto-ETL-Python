# Desafio de projeto (ETL com Python)

**Contexto:** Você é um cientista de dados no Spotify e recebeu a tarefa de envolver seus clientes de maneira mais personalizada. Seu objetivo é usar o poder da api do Spotify para criar dashboards personalizadas que serão entregues a cada cliente baseado nas músicas, álbuns e artistas entre 2021 e 2023.

# Condições do Problema:

- Você recebeu os dados, em formato JSON ('Streaming_History_Audio_2021-2023.json'), com 21 colunas e mais de 10 mil linhas.
- Seu trabalho é consumir o endpoint https://api.spotify.com/v1/search (API do Spotify) para obter os dados do ID e da imagem do artista.
- Depois de obter os dados, você vai usar a base de dados das músicas para juntar a imagem do artista em uma nova coluna.
- Depois que os dados estiverem limpos e as colunas que não serão utilizadas devem ser apagadas
