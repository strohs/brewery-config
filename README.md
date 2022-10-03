# Brewery Microservices Configuration Repository

This repository holds spring cloud configurations for the Brewery microservices:
- beer-service
- brewery-gateway
- inventory-service
- order-service


`application-local` properties are configurations designed to run on a LOCALHOST under spring boot's embedded 
servlet container. URIs are configured to use `localhost` as the default domain.


`application-local-docker` configurations are for microservices running as docker containers. URIs will be configured
to point to docker compose service names