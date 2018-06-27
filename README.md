# Lyrify

Lyrify is a decentralized application (DApp) that allows users to save song lyrics, to the Ethereum blockchain. This enables users to permanently store a record of their written work in the blockchain, which can be used to protect content creators against copyright infringement and hence protecting their creativity.

## Getting Started

Follow these instruction:

### Installing

Follow these instructions to get a development environment up and running:

Clone the repository

```
git clone https://github.com/sayak119/Lyrify.git
```

Install dependencies

```
cd Lyrify
npm i
```

Install testrpc and truffle

```
npm install -g ethereumjs-testrpc
npm install -g truffle
```

Run testrpc in a terminal window

```
testrpc
```

To compile and migrate the Solidity contracts, run the following commands in another terminal window:

```
truffle compile
truffle migrate --reset
```

Run the dev script to start the project

```
npm run dev
```
You will be pointed to **localhost:3000**.

## Setting up MetaMask

1. On the MetaMask login page, click the **Restore from seed phrase** link.
2. Copy and paste the 12-word mnemonic from the testrpc output into the Wallet Seed textbox.
3. Change the network to **Localhost 8545** in the metamask web extension.
4. When clicking the Submit button on the home page, a MetaMask popup will ask you to confirm the transactions. You may need to transfer ETH from the current account to the sending account (if different) for the transaction to go through. Congrats! This transactions will be mined into the Ethereum blockchain!

## Technologies Used

* [Truffle](https://github.com/trufflesuite/truffle) - Popular Ethereum development framework.
* [Web3js](https://github.com/ethereum/web3.js/) - Ethereum JavaScript API.
* [Solidity](https://github.com/ethereum/solidity) - Contract-oriented programming language.
* [Open Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - Framework to build secure smart contracts on Ethereum.
* [MetaMask](https://chrome.google.com/webstore/detail/metamask/) - Extension for accessing Ethereum enabled DApps in Google Chrome browser.


## YouTube Video

[Demo Video](https://www.youtube.com/watch?v=05_ONNYbL4U)
