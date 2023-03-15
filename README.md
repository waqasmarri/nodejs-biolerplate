
# RESTful API Node Typescript Server Boilerplate

By running a single command, you will get a production-ready Node.js TypeScript app installed and fully configured on your machine. The app comes with many built-in features, such as authentication using JWT, request validation, docker support, API documentation, etc. For more details, check the features list below.

## Quick Start
Clone the repo:

```bash
git clone https://github.com/asim47/nodejs-ts-express-mongoose-swagger-eslint-docker-prettier-husky-2023.git
cd nodejs-ts-express-mongoose-swagger-eslint-docker-prettier-husky-2023
```

Install the dependencies:

```bash
npm install
```

To run the dev server with docker:

```bash
make dev
```

or

```bash
docker-compose up
```

## Features

- **ES9**: latest ECMAScript features
- **Static Typing**: [TypeScript](https://www.typescriptlang.org/) static typing using typescript
- **Hot Reloading**: [Concurrently](https://github.com/open-cli-tools/concurrently) Hot realoding with concurrently
- **NoSQL database**: [MongoDB](https://www.mongodb.com) object data modeling using [Mongoose](https://mongoosejs.com)
- **Logging**: using [pino](https://github.com/pinojs/pino)
- **API documentation**: with [swagger-jsdoc](https://github.com/Surnet/swagger-jsdoc) and [swagger-ui-express](https://github.com/scottie1984/swagger-ui-express)
- **Environment variables**: using [dotenv](https://github.com/motdotla/dotenv)
- **Security**: set security HTTP headers using [helmet](https://helmetjs.github.io)
- **Santizing**: sanitize request data against xss and query injection
- **CORS**: Cross-Origin Resource-Sharing enabled using [cors](https://github.com/expressjs/cors)
- **Docker support**
- **Linting**: with [ESLint](https://eslint.org) and [Prettier](https://prettier.io)
- **Editor config**: consistent editor configuration using [EditorConfig](https://editorconfig.org)
- **Husky**: for lint checking on commit

