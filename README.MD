# DependIt 

## Aim
This product aims to easily manage and visualize the dependencies between your services and third party services if desired.

Visualizind dependencies between services will help doing impact analysis before making a change, alerting consumers if the change is breaking and determining the minimum set of tests across all of your services before and after deployment.

## Dependencies and Technologies
This product has too, dependencies.

### Docker
We'll make heavily use of Docker containers in this product because we think that it greatly simplifies the development process.

https://github.com/docker

### ArangoDB
Data will be held in an ArangoDB instance which is a great open source multi-model database. ArangoDB has enterprise offerings too if enterprise level support is needed while using this product. For the sake of portability the ArangoDB database will be used inside a Docker container, but ArangoDB has a Kubernetes operator option inside their enterprise package.

https://github.com/arangodb/arangodb/

### Golang
API layer is written in Golang, which is an open source imperative programming language developed by Google. API layer will make managing products and their dependencies intuitive so the API's user can do these operations without meddling with ArangoDB's Query Language AQL.
https://github.com/golang/go
