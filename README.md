# GoBarber-API

GoBarber-API is server-side of ecosystem developed for manage the barber service schedule.

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run this project locally you must have installed

- [Node](https://nodejs.org/en/) (v10 or later)

- [Yarn](https://yarnpkg.com/pt-BR/) or [NPM](https://www.npmjs.com/)


Clone repo:

```
git clone https://github.com/paulohlips/gobarber
```

Inside repo folder:

```
yarn
```

or

```
npm install
```

### Running GoBarber-API

Starting app on developer mode:

```
yarn dev
```

The api will be listening on

```
http://locahost:3000
```

### Routes

```
POST/users - Create user
PUT /users/{id} - Update user
```

```
GET/providers - List providers
GET/providers/:providerId/available - List avaible provider
```

```
GET /appointment - List all appointment
POST/appointment - Create appointment
DELETE/appointment/{id} - Delete appointment
```

```
GET/notifications - List notifications
PUT//notifications/:id - Set notification as read
```

```
GET /schedule - List schedule
```

```
POST /files - Image profile upload
```

```
POST /session - Create new session
```


## Built With

- **NodeJS** — A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **ExpressJS** — A Node js web application server framework.
- **MongoDB** — A document-oriented NoSQL database used for high volume data storage.
- **Mongoose** — An Object Data Modeling (ODM) library for MongoDB and Node. js.
- **PostgreSQL** — A  a powerful, open source object-relational database system that uses and extends the SQL language.
- **Sequelize** — A is a powerful library in Javascript that makes it easy to manage a SQL database.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
