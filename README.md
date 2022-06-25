# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
We’re going to be making a smaller version of ENS on the Polygon blockchain: we’ll let anyone buy a domain NFT and point it to something. This is awesome cause once your contract is on the blockchain, any data it has will be universal! Anyone can read the names and look at what it’s pointing to. And because blockchains are so unstoppable, no one can remove your data or kill your epic domain