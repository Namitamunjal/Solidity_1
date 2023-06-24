Overview

This repository is a solidity contract in which we will be creating our very own token.We will be using different concepts like various datatypes, mapping,functions,conditions,access specifiers etc.
This solidity contract will allow the user to mint and burn tokens when needed using the functions.


Contract details

Contract name: MyToken


Functions

mint : 

This function takes two parameters,one address and another uint(positive number).This mint function increases the total supply by the number passed and increases the balance of the “sender” address by that amount.

burn :

This function takes two parameters, one address and another one uint(positive number).This function first checks if the balance of "sender" is greater than or equal to the amount that is supposed to be burned.If this condition is met, then it will then deduct the value from the total supply and from the balance of the “sender”.


Deployment and Usage:

Contracts in solidity can be deployed in following ways:

1. Compile the smart contract (you can set it to auto compile) in any Solidity Compiler like here we have used remix.

2.Deploy the contract on Ethereum Network.



Deployment Environment

This contract can be deployed in any version of solidity between 0.7.0 to 0.9.0.


Author

Namita Munjal

namitamunjal27@gmail.com
