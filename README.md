# NestJS Authentication: JWTs, Sessions, logins, and more! | NestJS PassportJS Tutorial

## Sumary
- [Description](#description)
- [Topics](#topics)
- [Dependecies](#dependecies)
- [Installation](#installation)
- [Running the app](#running-the-app)
- [Test](#test)

## <a name="description"></a> Description
- Repository for notes and putting into practice what was taught in the course
- Video course: [NestJS Authentication: JWTs, Sessions, logins, and more! | NestJS PassportJS Tutorial](https://youtu.be/_L225zpUK0M)

## <a name="topics"></a> Topics
- UsersService
- AuthService
- Implementing passport-local strategy (username/password login)
- AuthGuards
- Summary of local login flow
- Guard to check if user is authenticated
- Setting up sessions
- Summary of login with sessions flow
- Setting up JWT strategy, signing and validating
- Summary of JWT strategy flow

## <a name="dependecies"></a> Dependecies
- [Nest](https://github.com/nestjs/nest) - framework TypeScript
- [Node.js](https://nodejs.org/en) - is an open-source, cross-platform JavaScript runtime environment
- [passport-npm](https://www.passportjs.org/packages/passport-npm/) - Passport strategy for authenticating an npm client.

## <a name="installation"></a> Installation

```bash
$ npm install
```

## <a name="running-the-app"></a> Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## <a name="test"></a> Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```