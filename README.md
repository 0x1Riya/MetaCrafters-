# MetaCrafters - MyToken
MyToken is a simple ERC-20 compliant token smart contract built on the Ethereum blockchain using Solidity programming language. This contract enables the creation, minting, and burning of a custom token called ORCH.

# Overview
This contract defines the following variables and functions:

# Variables
tokenName: A public string variable that stores the name of the token.
tokenAbbrv: A public string variable that stores the abbreviation of the token.
totalSupply: A public uint variable that stores the total supply of the token.
balances: A mapping that stores the balance of each address that holds the token.

# Functions
mint: A public function that creates new tokens and assigns them to the specified address. It takes two parameters: _address (the address to which the tokens will be assigned) and _value (the number of tokens to create).
burn: A public function that destroys existing tokens from the specified address. It takes two parameters: _address (the address from which the tokens will be destroyed) and _value (the number of tokens to destroy).

# Deployment
This contract can be deployed on the Ethereum network using Solidity compiler version 0.8.18 or newer.

# License
This project is licensed under the terms of the MIT license.




 
