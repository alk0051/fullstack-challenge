<img src="logo-clubpetro.png" alt="Clubpetro" width="300">

# ClubPetro/fullstack-challenge
## Instruções para a execução desse projeto:

#### Instale o <a href="https://www.docker.com/">Docker</a> em sua maquina e execute os seguintes comandos:
Cria um container docker:
```bash 
# docker run --name fullstackchall -e POSTGRES_PASSWORD=clubpetro -d -p 5432:5432 postgres
```
Incia o container criado:
```bash 
# docker start fullstackchall
```
Entra no terminal do postgres:
```bash
# psql -U postgres
```
Cria um banco de dados chamado places:
```bash
psql=# CREATE DATABASE places;
```


#### Faça um clone desse repositorio em seu computador
#### Navegue usando seu terminal ate a pasta do projeto 
#### Na pasta backend execute o comando `yarn` e em seguida `yarn start` e com outro terminal execute os mesmos comandos na pasta frontend
#### A aplicação vai abrir no endereço ```localhost:3000``` do seu navegador.



&nbsp;


## Tecnologias usadas 💻

### Back-end 

#### - ✅ NodeJS
#### - ✅ NestJS
#### - ✅ Typescript
#### - ✅ TypeORM
#### - ✅ Postgres
#### - ✅ Docker
#### - ✅ Jest


### Front-end 

#### - ✅ React
#### - ✅ Typescript
#### - ✅ styled-components
#### - ✅ react-input-mask
#### - ✅ Material-UI
