# HEADING
This Solidity source code implements a simple smart contract in which we create a token and some functionality to create and burn tokens. This smart contract demonstrates the basic syntax and functionality as well as the use of various language features such as mappings, functions and conditional statements.

## Description
The smart contract includes public variables to store the state of the token. It includes the name of the token, its abbrevation and total supply.
Next there is a mapping between addresses and tokens. Finally there are functions to mint and burn tokens. These functions naturally update the total supply and there is further check to ensure that total supply doesn't go below 0.

## Getting Started
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension. Copy and paste the code from the text.sol file into the file you created.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to the version specified in the source file.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with the functions by using a default address and then minting and burning tokens on that address.