# Template project for TS library repos

## Usage

1. Implement your library, see: 
    * HelloWorld.ts
    * HelloWorld.test.ts
    * index.ts
    
1. update this README.md with you actual library description, don't forget to describe:
    * build
    * tests
    * ADR

1. upon a change bump the version ``npm version patch -m "Upgrade to %s for reasons"``,
see [versions](https://docs.npmjs.com/cli/version.html)

## Build 
 
`tsc` or `npm run build`
 
## Tests
 
`npm test` - Runs all tests
`npm run test:unit` - Runs unit tests only
`npm run test:integration` - Runs integration tests only

## Linting

`npm run lint`

## Changelog

## Architectural decisions records
