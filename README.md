<h1 align="center">
  TODO Logo
  <br>
    Clank is the discord bot that will make you go nuts
  <br>
  <br>
</h1>

<p align="center">
  <br>
  TODO: CI Banner
  <br>
  <br>
  Made with :heart: by SMILE Discord Team
</p>

## Development Requirements

- Node.js: [Current](https://nodejs.org/en/)
- Yarn: [Current](https://classic.yarnpkg.com/lang/en/docs/install)
- (Optional) [Visual Studio Code](https://code.visualstudio.com/)

## Recommended VSC Setup

### Extensions

- [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)
- [Jest Snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets)
- [VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

### Config

- Set Format on Save

Go to Settings and set:

```
Format On Save: On
Default Formatter: Prettier
```

## Getting Started

### Setup

1. Clone this repository

2. Navigate to the folder using the terminal

```
cd clank
```

3. Install dependencies

```
yarn
```

4. Add .env files - Check .env.example

.env
.env.development
.env.production

## Run

Run in development mode

```
yarn dev
```

Run in production mode

```
yarn start
```

### Build

```
yarn build
```

### Tests

Run unit tests

```
yarn test
```

Run tests using watch

```
yarn test:watch
```

Run tests and output coverage folder

```
yarn test:coverage
```

### Lint & Format

Print ESLint errors and warnings

```
yarn lint
```

Fix ESLint errors and warnings

```
yarn lint:fix
```

Note: You may need to fix some by hand

Fix Prettier errors and warnings

```
yarn format
```

## Commands Format

```
clank | c <command> <params>
```

## Features

- [ ] Play Music - by link or name (have music queue)
- [ ] Stop Music
- [ ] Meme Generator

## Tech Stack
