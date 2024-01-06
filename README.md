# API Gateway en Go para arquitectura de microservicios

Proyecto de ejemplo basado en un tutorial de microservicios con Go para una API Rest con autenticacion via JWT token

## Arquitectura

El proyecto se comunica con 3 microservicios en Go mediante gRPC.

### Microservicio de Autenticacion:

Proporciona los endpoints para Login, Registro y Validacion de Token via gRPC para autenticacion.

`localhost:50051`

### Microservicio de Productos

Proporciona endpoints para la administracion basica de Productos.

`localhost:50052`

### Microservicio de Ordenes

Proporcione los endpoints para la gestion basica de Ordenes con Respecto a Productos y Usuarios.

`localhost:50053`

## Para iniciar el API Gateway

Debe estar en ejecucion los microservicios.

`make server`