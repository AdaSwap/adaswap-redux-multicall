# MultiCall

A React + Redux library for fetching, batching, and caching chain state via the MultiCall contract.

# AdaSwap redux multicall
Forked from the [Uniswap redux multicall](https://github.com/Uniswap/redux-multicall).

## Usage

The usage of this library is similar to [RTK Query](https://redux-toolkit.js.org/rtk-query/overview#create-an-api-slice).

### Before build

* Run `yarn install`
* Run `yarn contracts:compile`

### Build

* Run `yarn build`

## Publish to npm
1. Change **name** and **version** in package.json file
2. Run `yarn contracts:compile`
3. Run `npm publish --access public`