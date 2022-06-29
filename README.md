## Tutorial Link

- [Blockchain App Using Ethereum Smart Contracts and Solidity](https://www.youtube.com/watch?v=coQ5dg8wM2o&t=404s)

## Important Links

- [Create a personal blockchain using ganache](https://trufflesuite.com/ganache/)
- [Truffle framework](https://trufflesuite.com/)

## Install truffle

- ``npm install -g truffle@5.0.2``

## Initialize truffle

- ``truffle init``

## Run the migration

- ``truffle migrate --reset``

## Check the smart contract that is deployed to the blockchain

- ``truffle console``
- ``todoList = await TodoList.deployed()``

### Check address of the smart contract

- ``todoList.address``

### Check the task count

- ``todoList.taskCount()``
- ``taskCount = await todoList.taskCount()``
- ``taskCount.toNumber()``

