# BlockVote
### Made by Ualikhan Kamarov, Alibi Kemelbek, Ali Atchibayev, Beksultan Nalibek, Nauryzbai Tasbulat
This is an application to implement voting in solidity smart contract using ReactJS technology. 

## Installation

After cloning the repository, we want to install the packages using

```shell
npm install
```

First need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the CONTRACT ADDRESS and copy it in the .env file. We are using volta testnet for our project.

Once you have pasted your PRIVATE KEY and CONTRACT ADDRESS in the .env file, simply run command

```shell
npm start
```

Connect to the Metamask and you are welcome!
Thanks!
