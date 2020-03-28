# SupplyChain by Konstantin Ullrich
## Setup
**IMPORTANT**: You need to have npm and truffle already installd
1. Checkout the GitHub Repo
```
$ git clone git@github.com:konstantinullrich/EthereumCoffeeSupplyChain.git
```
2. Install dependencies using npm
```
$ cd EthereumCoffeeSupplyChain
$ npm install
```
3. Create .secret file

Create a file `.secret` in the root directory of this project containing the mnemoric seed or the private key of your Ethereum wallet 

4. Run Truffle tests
```
$ truffle develop
truffle> test
```

5. Compile Smart Contracts using Truffle
```
$ truffle compile
```

5. Deploy Smart Contracts to the Rinkeby Testnet
```
$ truffle migrate --network rinkebyk
```

## Project WriteUp
The UML-Diagrams are in `./images`

### Libraries used
The only Library used was `truffle-hdwallet-provider` to deploy the Smart Contracts to the Rinkeby Testnet using infura.

### Usage of IPFS
The IPFS (Interplanetary File System) wasn't used for this project, but it should be used for similar projects to provide a fully decentralized service. It wasn't used because I considered it out of Scope.

## Deployd on the Rinkeby Testnet
- [SupplyChain](https://rinkeby.etherscan.io/address/0xb5e89c7febdea24aba3c06208f141ad20be65a05) ([Transation](https://rinkeby.etherscan.io/tx/0xd124bbb03a3f34702d838fbea27e38dc2be6c3fdc6fc44e9d38754cf62f07cfc))
- [Farmer Role](https://rinkeby.etherscan.io/address/0xa335eb3b0702ee9af1dffb514ec529437047f306) ([Transation](https://rinkeby.etherscan.io/tx/0x5d343a0d1f6a026187e33a15258e99ef482824aa827e2e7efac5241ec171be3d))
- [Distributor Role](https://rinkeby.etherscan.io/address/0x21d2e0f3a7b883c3bc47534877a9a43096b60485) ([Transation](https://rinkeby.etherscan.io/tx/0x9c3edc9a45400a3aa5bf75db4ecf9899aaeea1e10bf5889da4dba72b8003e36f))
- [Retailer Role](https://rinkeby.etherscan.io/address/0x2c6efa8a53819e46b907b83b3636b4c696a50c7c) ([Transation](https://rinkeby.etherscan.io/tx/0x1d44f34310f7c2c1832f4237f491ebc7b748c391c129cafd8ee5796d647a0bb4))
- [Consumer Role](https://rinkeby.etherscan.io/address/0x4bcb883814afe6b8fa3aa82b609cbed67d825f30) ([Transation](https://rinkeby.etherscan.io/tx/0x445cff8e0d7920329cf4086230ddb6b86addd9c1165a342d19ea1898ba93dd28))