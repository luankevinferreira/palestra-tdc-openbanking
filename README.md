# Palestra TDC Open Banking GFT

Este repositório contém o código fonte utilizado na palestra da GFT sobre Open Banking que aconteceu dia 24/03/2021 no TDC.

## Requisitos

- [NodeJS](https://nodejs.org/en/)
- [Instalar Stoplight Prism](https://github.com/stoplightio/prism#-installation-and-Usage)

## Requisitos parte 2

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Passo a passo

1. Executar o seguinte comando: `prism mock https://raw.githubusercontent.com/OpenBanking-Brasil/areadesenvolvedor/master/documentation/source/swagger/swagger_channels_apis.yaml`;
2. Realizar as requisições para a API utilizando a ferramenta Postman;

## Passo a passo parte 2

1. Executar o seguinte comando na pasta **prism-multi-example**: `docker-compose up`
2. Realizar as requisições para qualquer API do Open Banking utilizando a ferramenta Postman;

Obs.: É possível importar as coleções do Postman disponíveis neste repositório (pasta `collections-postman`) para facilitar a navegação;
  
## Referências

- [Site Área do Desenvolvedor Fase 1](https://openbanking-brasil.github.io/areadesenvolvedor/#introducao)
- [Site Área do Desenvolvedor Fase 2](https://openbanking-brasil.github.io/areadesenvolvedor-fase2/#introducao)
- [Repositório Github Área do Desenvolvedor Fase 1](https://github.com/OpenBanking-Brasil/areadesenvolvedor)
- [Repositório Github Área do Desenvolvedor Fase 2](https://github.com/openbanking-brasil/areadesenvolvedor-fase2)
- [Open Banking Mock API Fase 1](https://github.com/OpenBanking-Brasil/mock-api)
- [Stoplight Prism website](https://stoplight.io/open-source/prism/)
- [Guia de instalação Stoplight Prism](https://github.com/stoplightio/prism#-installation-and-Usage)
- [Documentação Stoplight Prism](https://meta.stoplight.io/docs/prism/README.md)
- [API de produção dos participantes](https://data.directory.openbankingbrasil.org.br/participants)
- [Consumo dos campos da API dos participantes](https://openbanking-brasil.github.io/areadesenvolvedor-fase2/#participantes-open-banking-brasil)
- [Artigo sobre o Open Banking](https://blog.gft.com/br/2021/02/23/como-o-open-banking-funciona-na-pratica/)
- [Ferramenta Postman](https://www.postman.com/downloads/)
- [Collection do Open Banking no Postman](https://app.getpostman.com/join-team?invite_code=c9b7529ae11f615366a03067558e9c44&ws=0234a02b-34b1-4f4d-af57-e0ffab23a8e9)
- [Open Banking Banco Central do Brasil](https://www.bcb.gov.br/estabilidadefinanceira/openbanking)