## REST API Docs 

```javascript
https://itp9177.github.io/
```

## Quick Start

#### With docker-composer

```javascript
git clone https://github.com/itp9177/Spring-MVC-Rest-Grpc-Graphql-Monolithic-POC.git
docker-compose -f docker-compose.yml up
```

#### API endpoints

```javascript
REST    localhost:8081/rest
GraphQL localhost:8081/graphql
MVC     localhost:8081/mvc
gRPC    localhost:9090

```
#### Keycloak dashboard

```javascript
localhost:8080

```
## Roadmap

- [x]   initial project
- [x]   liquibase scripts for initial database
- [x]   spring security initial config for each api
- [x]   keycloak and resouces server
- [x]   initial openapi3 specs
- [x]  initial grpghql support
- [x]  initial protobuf/grpc support
- [ ]  grpc security intergrate to spring security
- [ ]  update restapi spec + implement functionality
- [ ]  demo mvc frontend
- [ ]  grpc service implementation
- [ ]  graphql implementations
- [ ]  create docker images
- [ ]  demo angular frontend

## License

[MIT](https://choosealicense.com/licenses/mit/)

