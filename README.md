# Blockchain - Bank Account With Multiple Approvals

This project provides a smart contract that allows for creating joint bank accounts. Each bank account can have up to 4 owners, each of which must approve any withdrawl of funds. As well as completed contract there is are automated test cases and a slim front-end applications that allows you to interact with some functionality of the contract. 

## Getting Started

To test and deploy the smart contract follow the steps below.

1. Install [Node.js](https://nodejs.org/en/download/)
2. Clone the repository: `git clone https://github.com/ibrahim0099/joint-bank-account`
3. `cd joint-bank-account`
4. `npm install`
5. To test the contract run `npx hardhat test`
6. To deploy the contract to your `localhost` network do the following:
   - `npx hardhat node`
   - `npx hardhat run --network localhost ./scripts/deploy.js`


