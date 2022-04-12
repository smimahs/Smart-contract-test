# Smart-contract-test

Start deploying your first smart contract with [truffle](https://trufflesuite.com/tutorial/)

## Background

In the project we have 2 simple function for adapt maximum 16 pets.

## Installation

First install truffle: 

```bash
npm install -g truffle
```

To verify that Truffle is installed properly, type `truffle version` on a terminal.

## Usage

We've created a special Truffle Box just for this tutorial called pet-shop, which includes the basic project structure as well as code for the user interface. Use the truffle unbox command to unpack this Truffle Box.

```bash
truffle unbox pet-shop
```

Truffle can be initialized a few different ways. Another useful initialization command is `truffle init`, which creates an empty Truffle project with no example contracts included. For more information, please see the documentation on Creating a project. 


## Directory structure¶

The default Truffle directory structure contains the following:

    contracts/: Contains the Solidity source files for our smart contracts. There is an important contract in here called Migrations.sol, which we'll talk about later.
    migrations/: Truffle uses a migration system to handle smart contract deployments. A migration is an additional special smart contract that keeps track of changes.
    test/: Contains both JavaScript and Solidity tests for our smart contracts
    truffle-config.js: Truffle configuration file

## Compiling and migrating the smart contract
Now that we have written our smart contract, the next steps are to compile and migrate it.

### Compilation
```bash
truffle compile
```

### Migration
Before migration we need to have a blockchain running like Ganache. First we start Ganache and then:

```bash
truffle migrate
```

## Testing
Truffle is very flexible when it comes to smart contract testing, in that tests can be written either in JavaScript or Solidity. In this tutorial, we'll be writing our tests in Solidity.

after writing the tests we can run the tests like this:

```bash
truffle test
```




## License
[Truffle](https://trufflesuite.com/tutorial/)