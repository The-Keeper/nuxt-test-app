# Nuxt-app

Example stack application Nuxt, Postgres and PostgREST

### Tech stack:
- Docker-compose
- Nuxt
- PostgREST
- Postgres DB 
- Swagger UI (Rest schema)

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# Stop all the docker containers (docker-compose down)
$ yarn stop

# Inspect with swagger-UI
$ npx open-swagger-ui "http://127.0.0.1:8080" 

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

