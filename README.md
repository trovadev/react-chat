# react-chat

## Development server
- ``npm start`` dentro do projeto levanta o servidor em `http://localhost:8080`

## Utilizando docker

- ``docker-compose up -d`` dentro do projeto levanta o container
- ``docker exec trovadev-react-chat bash`` acessa o container, permitindo utilizar os comandos do npm. Podendo sair com ``exit``
  - Para subir o servidor de desenvolvimento em `localhost:8080` deve ser usado ``npm start`` dentro do container
- ``docker-compose down`` dentro do projeto para e remove os containers
