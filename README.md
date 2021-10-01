# React Dapp Sample Project

This codebase was obtained after following the tutorial [The Complete Guide to Full Stack Ethereum Development](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13)

## Getting started

Here's how to deploy this project

1. Clone the repo

```sh
git clone https://github.com/nicolas-sanch/react-dapp
cd react-dapp
```

2. Install the dependencies

```sh
npm install
```

2. Start the local test node

```sh
npx hardhat node
```

3. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Update __src/App.js__ with the values of your contract addresses (`greeterAddress` and `tokenAddress`)

5. Run the app

```sh
npm start
```
## Deploying and using Ropsten test network

1. Create your .env file with your own values

```sh
cp .env.example .env
vi .env
```

2. Update __/hardhat.config.js__ by uncommenting the `ropsten` block

3. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network ropsten
```