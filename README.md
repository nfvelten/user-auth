# user-auth

Para rodar a aplicação é simples.

# Clone o repositorio.
```bash
$ git clone https://github.com/oxyli6z/user-auth.git
```
# Entre no repo.
```bash
$ cd user-auth/
```
# Entre na pasta da api.
```bash
$ cd api
```
# Instale as dependências 
```bash
$ yarn install
```
# Saia da pasta da api.
```bash
$ cd ../
```
# Suba o docker-compose
```bash
$ docker-compose up dev
```
# Após iniciar o docker-compose, caso um erro apareça, iremos entrar na pasta da api.
```bash
$ cd api
```
# E migrar o banco de dado
```bash
$ npx prisma migrate dev --name init
```
