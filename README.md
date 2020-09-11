# app-budget-backend

An application API for controll your finances. GoFinances is an application to control your financial expenses in a simple and elegant way.

## How to install

**Create your docker container**

```
docker run --name go-finances -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

💭🔥 Don't forget to create the 'go-finances' database before running the project

**Clone the repository**

```
$ git clone  https://github.com/martins20/GoFinances.git

$ cd GoFinances

$ yarn install

$ yarn typeorm migration:run

$ yarn dev:server
```

**You can download the `insomnia.json` file and import in your local insomnia to test the routes manually**

### Features

- [x] User can create an transaction
- [x] User can edit an transaction
- [x] User can delete a transaction
- [x] User can list a transaction

### Techs used in this project

```
typescript
typeorm (using decorators)
express
pg (postgres)
express
jest
multer
reflect-metadata
csv-parser
express-async-errors
```
