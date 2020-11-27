# Micro Exchange
As part of my master thesis I want to include a simple token micro-economy. I like to do a simple simulation where value is transferred between token owners to buy or sell a set of 5 different products. Basically what I want is to make an example with 5 to 10 different "agents" where each of them initiate with different amounts of tokens, something between 100 and 100000 tokens, after this I like to randomly set them lose to transact these values from one to another for a period of one day making transfers every minute for example. After the day is complete, I like to see statistics on a graph, then run it again for a following day and compare results. These are some of the parameters:

Number of agents 10 (each agent should have a name)

Number of products 5 (each product should have a name and price for agents to buy -and sell-)

Number of random transactions 1440 ( this is a random transaction for each minute in one day)

Token price = 1cent

To start this I am using a tutorial from MESA which is very close to what I need to do. Part of the code is here and can be used. It just needs to be modified a little.

## Description

The current project creates hashes of the user offers using [Merkletree.js](https://github.com/miguelmota/merkletreejs#documentation) and stores them on [Volta](https://energyweb.atlassian.net/wiki/spaces/EWF/pages/702677023/Chain%3A+Volta+Test+Network) test network.



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Please make sure you've already installed Truffle and enabled the MetaMask extension in your browser.

```
* Truffle v5.1.26 (core: 5.1.26)
* Solidity >= v0.5.16 (solc-js)
* Node >= v12.16.3
* Web3.js >= v1.2.7
* Metamask Chrome extension (connected with Volta)
```

Note: Please follow the [steps](https://energyweb.atlassian.net/wiki/spaces/EWF/pages/703201459/Volta+Connecting+to+Remote+RPC+and+Metamask) to connect Metamask with Volta.

###  Installing
Follow the steps below to have development environment running:
1. Clone the repository:
```
$ git clone https://github.com/olisystems/alf-transparency.git
```

2. Change directory to `alf-transparency
` folder and install all requisite npm packages (as listed in `package.json`):
```
$ cd alf-transparency
$ npm install
```
3. Compile the smart contracts:
```
$ cd truffle
$ truffle compile
```
This will create the smart contract artifacts in folder `app\src\assets\js\contracts`.

4. Migrate smart contracts to `volta` chain:
```
$ npm run migrate
```

5. Test smart contracts:
```
$ npm run test
```

6. Compiles and hot-reloads for development, run the following command inside `app` directory:
```
$ cd app
$ npm run serve
```
Navigate to `localhost:8080` in your browser.

7. Compiles and minifies for production:
```
$ npm run build
```
## Built With

- [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts to make the web faster, safer, and more open.
- [Web3.js](https://web3js.readthedocs.io/en/v1.2.7/#web3-js-ethereum-javascript-api) - A collection of libraries which allow interacting with a local or remote ethereum node, using an HTTP or IPC connection.


## Contributing

Pull requests are welcome.

1. Fork the repository.
2. Create your new feature branch: `git checkout -b new-feature-branch`
3. Stage your changes: `git add .`
4. Commit the changes: `git commit -m "add commit message"`
5. `push` to the branch: `git push origin new-feature-branch`
6. Submit a `pull request`.