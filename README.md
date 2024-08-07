# Prerequisites

After cloning repository, you need to install these dependencies:
- NPM
- Cypress
- Cucumber -> @badeball/cypress-cucumber-preprocessor
- Cucumber -> @bahmutov/cypress-esbuild-preprocessor -D
- [dotenv](https://www.npmjs.com/package/dotenv)
- [eslint](https://www.npmjs.com/package/eslint)
- [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)
- [eslint-plugin-prettier](https://www.npmjs.com/package/eslint-plugin-prettier/v/4.0.0)
- globals
- [prettier](https://www.npmjs.com/package/prettier)

If you dont have the extensions already installed in VScode, you will need these for cucumber to work:
- Cucumber (Gherkin) Full Support -> Alexander Krechik
- Cuke Step Definition Generator -> Muralidharan Rajendran

## Initialize The Project

Once you open your framework, initialize it as a node.js project with the following command:

```bash
npm init -y
```

## Install Cypress

```bash
npm install cypress -D
```

## Install @badeball/cypress-cucumber-preprocessor
This preprocessor aims to provide a developer experience and behavior similar to that of Cucumber, to Cypress.

```bash
npm install @badeball/cypress-cucumber-preprocessor -D
```

## Install @bahmutov/cypress-esbuild-preprocessor

```bash
npm install @bahmutov/cypress-esbuild-preprocessor -D
```

## Install the dotenv dependency
This is used to protect sensitive or environment-specific data

Advantage: Secure and flexible test configurations
```
npm install dotenv -D
```
## Install Prettier

```bash

```

## Install eslint-config-prettier

```bash

```

## Install eslint-plugin-prettier

```bash

```
