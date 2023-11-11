#Solidity Contract

The `Assessment` Solidity smart contract in this repository shows off basic features including error handling. Additionally, we might employ front-end diplaying via MetaMask to communicate with the smart contract through a straightforward React application.

## Smart Contract

### Overview

The following elements are included in the {Assessment} contract:

**Constructor function** — this function, in our case, initializes the contract's balance to zero.
- **getBalance Function** Returns the amount that is currently outstanding in our account.
- **array_sum:** Updates the contract's balance by calculating the sum of the elements in an array.
- **product array:** updates the balance of the contract by multiplying the elements in an array.

### How to use

1. Install the `Assessment} contract on an Ethereum blockchain that is suitable.
2. To communicate with the MetaMask wallet, connect it. 

3. Employ the `array_sum} and `array_product} functions that are offered to carry out computations and update the contract's balance.

### Mistake Management

- In the `array_sum` and `array_product` functions, the `assert` statement is utilized to guarantee that the array length is larger than zero.
. The `array_product` method implements a custom error to verify the array length.

## Application for React

### Synopsis

An interface for interacting with the deployed {Assessment} smart contract is provided by the React application.

- **Connect Wallet:** Link the program to your MetaMask wallet.
- **Display Account:** Displays the Ethereum account that is linked.
- **Display Balance:** Shows the {Assessment} contract's current balance.
- **Array Sum and Product:** Toggle buttons to update the contract's balance by using the `array_sum` and `array_product` functions.

### How to Use

1. Install MetaMask in your browser.
2. Open the React application in a web browser.
3. Connect your MetaMask wallet.
4. View your account and the current balance.
5. Use the provided buttons to perform array calculations and update the contract's balance.

## Authors

- Mokshith P
- mokshithlucky06@gmail.com

## License

This project is licensed under the MIT License. 
