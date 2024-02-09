## Contract Puzzles

The goal of the Smart Contract puzzles was to work on reading smart contracts and writing good tests to modify those smart contracts.

Each Game contract has a storage variable called `isWon`:

```
bool public isWon;
```

The objective was to set this `isWon` to `true` without modifying the smart contract.


### Running the tests

First, install all the dependencies with `npm i`. Then, you can run all tests at once by running `npx hardhat test`. 

To run the test cases for the first game: `npx hardhat test test/game1Test.js`. Each Game contract will have a corresponding test file.

