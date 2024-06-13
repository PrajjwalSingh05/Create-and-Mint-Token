# Project Title: Create and Mint Token

# Description
MyToken is an ERC20 token contract with additional functionality for minting and burning tokens. The contract owner can mint new tokens to any address, while any token holder can burn tokens from their own balance. The contract uses OpenZeppelin's implementation of the ERC20 standard, providing a secure and well-tested base for token functionality.

# Features
* Minting: Only the contract owner can mint new tokens to any address.
* Burning: Any token holder can burn tokens from their own balance.

# Contract Details
* State Variables
 * address owner: Stores the address of the contract owner.
Constructor
solidity
Mints new tokens to the specified account.
Can only be called by the contract owner.
Parameters:
account: The address to which the tokens will be minted.
amount: The number of tokens to mint.
burn(uint256 amount) public

Burns the specified amount of tokens from the caller's account.
Parameters:
amount: The number of tokens to burn.
# Getting Started
* To run this program, you can use Remix, an online Solidity IDE:
* Go to the Remix website.
* Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol).
* Copy and paste the code provided above into the new file.
# Compile the Code
* Click on the "Solidity Compiler" tab in the left-hand sidebar.
* Make sure the "Compiler" option is set to "0.8.9" (or another compatible version).
* Click on the "Compile MyToken.sol" button.
* Deploy the Contract
* Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
* Select the MyToken contract from the dropdown menu.
* Click on the "Deploy" button.
* Interact with the Contract
# Authors
Prajjwal Singh
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
