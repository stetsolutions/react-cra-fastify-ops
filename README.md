# react-cra-fastify-ops

Ops starter using:

- Docker
- Kustomize 4
- Let's Encrypt
- Sealed Secrets 0.17

Submodules:

- [react-cra-mui-front-end](https://github.com/stetsolutions/react-cra-mui-front-end)
- [fastify-postgresql-back-end](https://github.com/stetsolutions/fastify-postgresql-back-end)


## Install

    npm i

## Setup

### Submodules

#### Add

    git submodule add https://github.com/stetsolutions/fastify-postgresql-back-end.git fastify-postgresql-back-end
    git submodule add https://github.com/stetsolutions/react-cra-mui-front-end.git react-cra-mui-front-end

#### Update

    npm run update

### Kubernetes

[https://github.com/stetsolutions/react-cra-fastify-ops/wiki/Kubernetes](https://github.com/stetsolutions/react-cra-fastify-ops/wiki/Kubernetes)

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



