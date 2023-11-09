# Creating a Token

This solidity program is a simple token creation program that implements basic fundamentals and functions to create a token. The purpose of this program is to introduce the idea of how a token is created in its basic sense.


## Description

This program is a simple contract written in solidity, solidity is specifically tailored to suit the creation of smart contracts for the blockchain, and whatever activities carried on the blockchain require a smart contract, including making a token. This contract is meant to show the basic idea of how a token is created at its basic level, which includes, adding more tokens and removing tokens.



## Getting Started

### Executing program

 * To test the program, first of all, select all the code in 'my token.sol" file, and copy it.
   
 * Go to the remix website at https://remix.ethereum.org/, you can use remix as an online solidity ide.
   
 * Once on remix, create a new file, by clicking the 'create new file' icon, and save/name the file with a .sol extension(e.g. myToken.sol).
   
 * paste the code in the newly created file.
   
 * To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile myToken.sol" button. or just press ctr + s
   
 * Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "myToken" contract from the dropdown menu, and then click on the "Deploy" button.
   
 * Once the contract is deployed, interactions with the contract happen by calling functions and checking the states of variables in the contract. There are two callable functions(mint & burn), a mapping data structure named balances, and three state variables(tokenName, tokenAbbrv, & totalSupply).

 * Click on the mint function, input an address and a value(that’s not negative), then click on the transact button which executes the function and adds the number of tokens specified to the address, which also increases the totalSupply.

 * to reduce/remove tokens, click the burn function, input, and a value(ensure the value is less than the balance of the address), and click on the transact button which executes the function and removes the number of tokens from the address, in turn, reducing the total supply.



## Authors

dev_Praise  
[@dev_Praise](https://twitter.com/dev_praise)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
