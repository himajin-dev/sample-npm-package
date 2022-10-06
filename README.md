# sample-npm-package

This is a sample npm package hosted at GitHub Packages.

## Install

Create `.npmrc`:

```
@himajin-dev:registry=https://npm.pkg.github.com
```

Install npm package:

```
npm install @himajin-dev/sample-npm-package
```

## Development

### Setup

Install dependencies:

```
yarn install
```

### Usage

Transpile to JavaScript:

```
yarn build
```

### Publish

Publish to GitHub Packages:

```
npm publish
```

If you are not logged in, log in to GitHub Packages:

```
npm login --registry=https://npm.pkg.github.com
```
