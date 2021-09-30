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

2. Create your .env file with your own values

```sh
cp .env.example .env
vi .env
```

3. Start the local test node

```sh
npx hardhat node
```

4. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Update __src/App.js__ with the values of your contract addresses (`greeterAddress` and `tokenAddress`)

6. Run the app

```sh
npm start
```
