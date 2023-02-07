# Brewery Microservices Configuration Repository

This repository holds spring cloud configurations for the Brewery microservices:
- beer-service
- brewery-gateway
- inventory-service
- order-service


Spring Cloud Config will attempt to connect to this repository and pull the configurations based on one of the two
profiles below:


## Configuration profiles
`application-local` properties are configured to run on a LOCALHOST under spring boot's embedded 
servlet container. URIs are configured to use `localhost` as the default domain.


`application-local-docker` configurations are for microservices running as docker containers on a localhost. 
URIs are configured to point to docker compose service names