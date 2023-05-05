# ada-spotify
Um gerenciador de músicas e playlists feito para funcionar através do terminal. Projeto final da disciplina Lógica de Programação II do LM Data Talents, curso de Data Science da Ada em parceria com a Leroy Merlin. Também inclui uma aplicação com a API do Spotify que foi utilizado para popular a base de dados do gerenciador de músicas e playlists.

* Arquivos .json \
Os arquivos albums.json, artista.json e playlists.json guardam informações sobre as musicas armazenadas no bando de dados, albums tem o nome do album e das musicas que estão nele, artistas tem o nome dos artistas e seus respectivos albums e playlists tem seus nomes e as musicas que contém.

* entrada.csv \
Possui os logins de usuario e administrador do sistema. Não é realmente uma segurança razoável, mas o projeto solicitava essa distinção no login.

* Spotify.ipynb \
Embora o gerenciador de músicas desse a opção de popular a base de dados manualmente, achei mais interessante criar essa aplicação utilizando a API do Spotify para criar essa base de dados inicial.

* ada_projeto.ipynb \
É a aplicação em si. Ela lê os arquivos, cria as estrutura de dados e realiza buscas de músicas, artistas, albums e playlists
