# base-api
Simple api using Express.js and Postgres

# Features
* Create user
* Login (with jwt)
* Update user

## Install packages from yarn or npm
```bash
yarn install
```
or 
```bash
npm install
```

## Environment Settings

### Docker Settings

#### Install Docker
You need install Docker(https://docs.docker.com/compose/install/)
After that, you can use `docker` 

#### Create an image
Use docker command to create an image postgres
```bash
docker run --name "name" -e POSTGRES_PASSWORD="pass" -d -p "port":5432 postgres
```
After that you can use another docker comand to start the container
```bash
docker start postgresdb
```
