# Microsserviços com Docker

Este projeto implementa uma arquitetura de microsserviços utilizando Docker. O objetivo é criar um ambiente escalável e independente para cada microsserviço, permitindo o desenvolvimento e a execução isolada dos mesmos. O projeto também utiliza o Docker Compose para facilitar a orquestração dos containers.

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Fabisgb/docker-microservices.git
   cd docker-microservices
2. Build os containers e suba os microsserviços:
   ```bash
   docker-compose up --build

## Estrutura
- app1/: Microsserviço 1
- app2/: Microsserviço 2
- docker-compose.yml: Orquestração dos containers

## Tecnologias Utilizadas
- Docker
- Docker Compose
- Microservices
