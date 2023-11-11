The `Assessment` Solidity smart contract in this repository shows off basic features including error handling. Additionally, we might employ front-end diplaying via MetaMask to communicate with the smart contract through a straightforward React application.

## Smart Contract

### Overview

The following elements are included in the {Assessment} contract:

The Contructor Function initializes the contracts balance to some amountinitially , in pur case it is 0.
The getbalance Function simply returns the amount that is currently in our account.
The Array Sum Function is an arithmatic function that updates the contract's balance by calculating the sum of the elements in an array. In our case the elements being added are 2,3,5,7. All these elememts will add up and will be shown as the balance of our account
The Array product Function is an arithmatic function that updates the contract's balance by calculating the sum of the elements in an array. In our case the elements being added are 2,5,7,9. All these elememts will multiplied and will be shown as the balance of our account

### How to use

You may run the Assessment.sol smart contract on gitpod which is a online ide for running smart contracts.

## Application for React
React.js is used to make a front end for our contract where we can interact with the contract.
On the front end, we start off with connecting our metamask wallet , we need to have meta mask previously installed on our browser .
Once the connection wiht the metamask wallet is done we will be abled to see our account balance and we can use the two functions mentioned in the Assessment.sol file , and see changes in the account balance.

Please note to run anything on the front end using the metamask wallet we will have to pay a certain amount of gas fee.

## Authors
Mokshith P
mokshithlucky06@gmail.com

## License

This project is licensed under the MIT License. 
