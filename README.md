<h3 align="center">Microservices</h3>

## 🧐 About <a name = "about"></a>
React/Node.js Microservices using Docker and GraphQL.

## ⛏️ Built Using <a name = "built_using"></a>

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
- [Node.js](https://nodejs.org/) - Open source server environment.
- [Docker](https://www.docker.com/) - Tool to create, deploy, and run applications by using containers.
- [GraphQL](https://graphql.org/) -  Data query and manipulation language for APIs.
- [Sequelize](https://sequelize.org/) - A Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.
- [Redux](https://redux.js.org/) - A JavaScript library for managing application state.

## 🐱‍🏍 Setup
In the main directory run:
```
docker-compose up
```

Run migrations:
```
docker-compose exec listings-service bash
yarn db migrate

docker-compose exec users-service bash
yarn db migrate
```

In another terminal go to /classifieds-app to install the dependencies with ```yarn install``` and then run:
```
yarn watch
```