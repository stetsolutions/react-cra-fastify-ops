# react-cra-fastify-ops

Ops starter using:

- Docker
- Kustomize
- Let's Encrypt
- Sealed Secrets

Submodules:

- [react-cra-mui-front-end](https://github.com/stetsolutions/react-cra-mui-front-end)
- [fastify-postgresql-back-end](https://github.com/stetsolutions/fastify-postgresql-back-end)

## Install

    npm i

## Fetch Sealed Secrets public key

    npm run fetch:cert

## Update submodules

    npm run update

## Deploy 

### Docker

#### Development

    npm run compose:dev

#### Production
    
    npm run compose:prod 

#### Staging

    npm run compose:staging

### Kubernetes 

#### Development

    npm run apply:dev

#### Production
    
    npm run apply:prod

#### Staging

    npm run apply:staging



