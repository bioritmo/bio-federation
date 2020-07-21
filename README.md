# BioFederation

É uma arquitetura que une múltiplos serviços de consumo de dados(rest/graphql) da Bio Ritmo em um
 único endpoint em Graphql.

## Requisitos

**Node 12+ (nvm)**
- Instalação via NVM
https://github.com/nvm-sh/nvm#installing-and-updating

**Docker**

 - Instalação Ubuntu:
 https://docs.docker.com/engine/install/ubuntu/
 - Instalação MAC:
 https://docs.docker.com/docker-for-mac/install/
 - Instalação Windows:
 https://docs.docker.com/docker-for-windows/install/

## Instalação/Execução

1 - Levantando com container
```
docker-compose up --build
```

2 - Levantando sem docker
```
npm install
npm run start
```

3 - Acessar GraphiQl
```
http://localhost:20002/
```

4 - Endpoint Graphql
```
http://localhost:20002/graphql
```

## Deploy Production
```
sls deploy --stage prod
```

## Deploy Staging
```
sls deploy
```


## Licença e Autoria

Grupo Bio Ritmo (c) 2020
