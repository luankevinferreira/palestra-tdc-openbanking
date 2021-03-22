# Palestra TDC Open Banking GFT

Este repositório contém o código fonte utilizado na palestra da GFT sobre Open Banking que aconteceu dia 24/03/2021 no TDC.

## Requisitos

- [NodeJS](https://nodejs.org/en/)
- [Instalar Stoplight Prism](https://github.com/stoplightio/prism#-installation-and-Usage)

## Requisitos parte 2

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Passo a passo

1. Executar o seguinte comando: `prism mock https://github.com/OpenBanking-Brasil/areadesenvolvedor/blob/master/documentation/source/swagger/swagger_channels_apis.yaml`;
2. Realizar as requisições para a API utilizando a ferramenta Postman;

Obs.: É possível importar o arquivo no Postman `api-canais-atendimento.postman_collection.json` que já contém as requisições para a API pré configuradas;

## Passo a passo parte 2

1. Executar o seguinte comando na pasta `prism-multi-example`: `docker-compose up`
2. Realizar as requisições para qualquer API do Open Banking utilizando a ferramenta Postman;

Obs.: É possível importar as coleções do Postman disponíveis neste repositório para facilitar a navegação;
  
## Referências

- [Site Área do Desenvolvedor Fase 1](https://openbanking-brasil.github.io/areadesenvolvedor/#introducao)
- [Site Área do Desenvolvedor Fase 2](https://openbanking-brasil.github.io/areadesenvolvedor-fase2/#introducao)
- [Repositório Github Área do Desenvolvedor Fase 1](https://github.com/OpenBanking-Brasil/areadesenvolvedor)
- [Repositório Github Área do Desenvolvedor Fase 2](https://github.com/openbanking-brasil/areadesenvolvedor-fase2)
- [Open Banking Mock API Fase 1](https://github.com/OpenBanking-Brasil/mock-api)
- [Stoplight Prism website](https://stoplight.io/open-source/prism/)
- [Guia de instalação Stoplight Prism](https://github.com/stoplightio/prism#-installation-and-Usage)
- [Documentação Stoplight Prism](https://meta.stoplight.io/docs/prism/README.md)