# Yardsale
Yardsale is a decentralized platform for P2P buying and selling of goods within a community. Users sell their goods as assets or create their own assets to be transacted. All transactions are mined as blocks on the ethereum blockchain (currently testnet only). Transactions are secure through solidity smart contracts to ensure that users' are not scammed and have no fear of interaction with others.
Yardsale is superior to other exchange platforms because all data is stored on the blockchain. Each transaction is immutable, so if users report a malicious seller or buyer, they will be forever known by all entities on the network. 

## Usage

This project is currently only availibe to be deployed locally
###Dependencies

1. Node.js
2. npm
3. solidity
4. ethereum

###Deployment

1. Download truffle
2. Download an ethereum client
3. start client 
4. run `truffle compile`
5. run `truffle migrate`
6. run `npm to build the app and serve it on http://localhost:8080`


## Common Errors

* **Error: Can't resolve '../build/contracts/MetaCoin.json'**

This means you haven't compiled or migrated your contracts yet. Run `truffle compile` and `truffle migrate` first.

Full error:

```
ERROR in ./app/main.js
Module not found: Error: Can't resolve '../build/contracts/MetaCoin.json' in '/Users/tim/Documents/workspace/Consensys/test3/app'
 @ ./app/main.js 11:16-59
```

#Credits:
The framework for this project was adapted from the trufflesuite webpack found here: https://github.com/trufflesuite/truffle-init-webpack
