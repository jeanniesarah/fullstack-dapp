# fullstack-dapp experiment

This is a working repository for a fullstack dApp. The project experiment lives in an early exploratory state.

---

**⚠️This is not production-ready or even alpha software. This project is in active development.⚠️**

---

Please do not try to build anything with this!

## About this project

This is a fullstack dApp consisting of an Ethereum smart contract connected to a React frontend using Metamask and Web3 tools. 

The util/interact.js contains the smart contract interaction, variables, and wallet functions to manage the logic, data, and rules of dApp then exports those functions to the frontend (HelloWorld.js component). 

The Alchemy Web3 endpoint listener detects when the message stored in the smart contract changes so you'll need to create an environment variables file:

```touch .env``` 

Add your [Alchemy Websocket Url](https://github.com/alchemyplatform/alchemy-docs/blob/master/guides/using-websockets.md):
```
REACT_APP_ALCHEMY_KEY=your_alchemy_app_websocket_url
```

## Install

```sh
npm install
```

## Usage

```sh
npm run start
```

## Run tests

```sh
npm run test
```
