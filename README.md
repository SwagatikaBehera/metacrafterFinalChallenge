# Create, Mint and Burn a Token using Solidity

This is a simple Solidity project that demonstrates the fundamental concepts of creating and managing a token. The project involves the creation, minting, and destruction (burn) of tokens. It serves as the final challenge in learning Solidity fundamentals with Metacrafters.

## Project Overview

This Project aims to provide a hands-on learning experience in understanding the basics of token creation and management on the Ethereum blockchain. Through this project, one will gain practical knowledge in writing Solidity smart contracts, interacting with tokens, and implementing core functionalities such as minting and burning.

## Key Features

The project includes the following key features:

1. Token Creation: The smart contract allows the creation of a new token with a specified name, symbol, and initial supply.

2. Minting: The contract enables the minting of new tokens, increasing the token supply and increases the balance of the sender address by that amount. This can be done by authorized addresses or as per specified conditions.

3. Burning: The contract allows authorized addresses or specified conditions to destroy (burn) tokens, reducing the token supply and deduct the same amount from senders address balance.


## Getting Started

### REQUIREMENTS

    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value.The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens.It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., token.sol). Copy and paste the following code into the file:

pragma solidity ^0.8.4;

contract MyToken {

}

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile token.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the Mint or Burn function by making it external function or click on tokenName, tokenAbbrv, totalSupply to view token Details. 

## Authors

Swagatika Behera

SwagatikaBehera

[@capslockon29](https://twitter.com/capslockon29)
