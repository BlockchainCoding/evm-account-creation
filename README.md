# Ethereum EVM Account Creation
This code shows how to interact with an EVM compatible blockchain using Node.js to programmatically create accounts.

The Ethereum Sepolia Testnet is used for this demostration.

## Prerequisites
- Node.js - tested with 20.7.0
- Ethers.js - tested with 6.6.5

## Installation
Clone the repository:
```
git clone https://github.com/BlockchainCoding/evm-account-creation.git
```

Change into new directory and install dependencies:
```
cd evm-account-creation;
npm install
```

## Usage
Enter the number of accounts you would like to create in the createAccount() function call at the end of the script and then use one of the methods below to run the script.

```
npm run createAccount
```
or
```
node createAccount.js
```