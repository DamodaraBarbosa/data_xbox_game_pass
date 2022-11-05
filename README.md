# Infos Xbox Game Pass

Esse projeto tem como objetivo agregar dados sobre o serviço de jogos da Microsoft, o Xbox Game Pass. Segundo a Wikipedia:

"Xbox Game Pass é um serviço de assinatura de jogos eletrônicos da Xbox Gaming and Entertainment, conglomerado da Microsoft, para uso com seu console Xbox One, 
Xbox Series X/S e Windows. Descrito como 'Netflix dos videogames', o Xbox Game Pass concede aos usuários acesso a um catálogo de jogos de diversas publicadoras
por um preço único de assinatura mensal." Disponível em: https://pt.wikipedia.org/wiki/Xbox_Game_Pass.

Existem diversas informações sobre os jogos presentes no serviço espalhaos pela internet, a ideia é centralizar essas informações e disponibilizá-las para a comunidade
a fim de permitir diferentes análises e insights relacionados ao Xbox Game Pass.

## Quais as informações contidas na base de dados?

Jogos, plataformas, status do jogo no serviço (se está incluso, foi removido ou ainda vai ser adicionado), data de lançamento, gênero do jogo, desenvolvedora, publicadora,
avaliações no Metacritic, gamerscore, entre outros dados.

## Como os dados foram obtidos?

A base dos dados é obtida aqui: https://docs.google.com/spreadsheets/d/1kspw-4paT-eE5-mrCrc4R9tg70lH2ZTFrJOUmOtOytg/edit#gid=0.
Mas boa parte deles foi obtida através de web scraping. Na pasta CSV files há uma grande quantidade de dados relacionados a biblioteca de jogos do Xbox (360, One e Series),
além de dados do site True Achievements e do agregador de notas Metacritic.

## Conteúdo dos notebooks

Web Scraping Xbox 360 Wikipedia: código para obtenção dos dados quanto a biblioteca de jogos do Xbox 360.

Web Scraping Xbox One Wikipedia: código para obtenção dos dados quanto a biblioteca de jogos do Xbox One.

Web Scraping Xbox Series Wikipedia: código para obtenção dos dados quanto a biblioteca de jogos do Xbox Series.

Web Scraping Xbox 360 Metacritic: código para obtenção dos dados do agregador quanto aos jogos de Xbox 360.

Web Scraping Xbox One Metacritic: código para obtenção dos dados do agregador quanto aos jogos de Xbox One.

Web Scraping Xbox Series Metacritic: código para obtenção dos dados do agregador quanto aos jogos de Xbox Series.

Concat Xbox Games: concatenação dos dados referentes a biblioteca de jogos da plataforma.

Concat Xbox Games Metacritic: concatenação dos dados referentes a biblioteca de jogos da plataforma no Metacritic.

Merge Infos Xbox Game Pass: agrega os dados obtigos nos códigos anteriores.
