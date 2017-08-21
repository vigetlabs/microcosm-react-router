# Contribution Guidelines

Thanks you for considering a contribution to microcosm-react-router!

## Before Starting

microcosm-react-router is built using tools written for
[nodejs](http://nodejs.org). We recommend installing Node with
[nvm](https://github.com/creationix/nvm). Dependencies are managed
through `package.json`.

You use the same node version we are developing with by running

```bash
nvm use
```

> You may need to run `nvm install` if you haven't installed the node version on `.nvmrc`

## Getting Started

All commands should be run using yarn. If you haven't switched to [yarn](https://yarnpkg.com/en/) yet, now's a great time!

> If you are familiar with npm then using yarn should be a breeze. You can keep using npm if you'd prefer but you will miss out on the safety and security of yarn

You can install dependencies with:

```bash
yarn install
```

## Testing

```bash
yarn test
```

For test coverage:

```bash
yarn run test:cov
open ./coverage/index.html
```

> Be sure to check the `./coverage` folder to verify all code paths are
touched.

## Conventions

**Consider master unsafe**, use [`npm`](https://www.npmjs.com/package/microcosm) for the latest stable version.

### Javascript

We use [`prettier`](https://github.com/prettier/prettier) to ensure
code style consistency. Run prettier against changes with:

```bash
yarn format
```

### Reviews

All changes should be submitted through pull request. Ideally, at
least two :+1:s should be given before a pull request is merge.
