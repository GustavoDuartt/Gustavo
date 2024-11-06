# Projeto de Testes com SWAPI

Este é um projeto de testes automatizados utilizando Jest e Axios para validar a resposta de diferentes endpoints da SWAPI (Star Wars API). O objetivo deste projeto é garantir que a API retorne os dados esperados sobre planetas, naves, filmes, personagens e espécies do universo Star Wars.

# Tecnologias Utilizadas

* Jest: Framework de testes para JavaScript.
* Axios: Biblioteca para fazer requisições HTTP.
* SWAPI (Star Wars API): API pública que fornece informações sobre o universo de Star Wars.
* Funcionalidade
* O projeto contém uma série de testes que fazem requisições à SWAPI e validam as respostas. Abaixo estão os testes que são realizados:

### Testes Realizados

*Teste 1: Verifica se a API retorna os dados corretos do planeta Tatooine.

`Endpoint: /planets/1/
Verifica se o nome do planeta é "Tatooine".
Teste 2: Verifica se a API retorna os dados corretos do planeta Alderaan.`

`Endpoint: /planets/2/
Verifica se o nome do planeta é "Alderaan".
Teste 3: Verifica se a API retorna os dados corretos da nave Millennium Falcon.`

`Endpoint: /starships/10/
Verifica se o nome da nave é "Millennium Falcon".
Teste 4: Verifica se a API retorna os dados corretos da nave X-wing.`

`Endpoint: /starships/12/
Verifica se o nome da nave é "X-wing".
Teste 5: Verifica se a API retorna os dados corretos do filme A New Hope.`


# Pré-requisitos

* Node.js instalado na sua máquina. Caso não tenha o Node.js, você pode baixá-lo aqui.
* npm ou yarn para gerenciar dependências.
* Como Rodar o Projeto
1. Clonar o Repositório
Clone este repositório para sua máquina local:

## bash

Copiar código
`git clone https://github.com/seu-usuario/swapi-tests.git`

2. Instalar as Dependências

*Acesse a pasta do projeto e instale as dependências necessárias com o comando:

bash
Copiar código
npm install
Isso irá instalar o Jest e o Axios, que são as bibliotecas utilizadas nos testes.

3. Executar os Testes
Para rodar os testes, use o comando:

bash
Copiar código
npm test
O Jest irá rodar todos os testes e você verá o resultado no terminal.
