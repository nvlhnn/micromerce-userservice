## Description

The micromerce project is a set of microservices that enables users to manage product, order, and user data. The project will consists of four main services:api-gateway, product-service, order-service, and user-service. 

Internal communication between services is done through gRPC. External communication is done via REST API, which is processed through api-gateway, and then forwarded to microservices using gRPC. JWT is used to ensure the security of external communication.

## Repositories

- https://github.com/nvlhnn/micromerce-userservice

## Installation

```bash
$ make proto
```

## Running the app

```bash
# development
$ make server
```
## Todo
- product service
- order service
- api gateway

## Author

- [Naufal Hanan](https://linkedin.com/in/nvlhnn)
