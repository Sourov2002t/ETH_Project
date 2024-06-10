# Metacrafters Project: Creating "Bitcoin Cash" (BCH): A Beginner's Guide to Building a Simple Token with Solidity

# Overview / Description 
Simplifying issues like supply management, balance tracking, and token generation, the "Bitcoin Cash" contract is a simple Ethereum token written in Solidity. 
"Bitcoin Cash" is the name of the token defined in the contract, and its symbol is "BCH". It has features to mint new tokens and burn old ones, as well as mappings to keep track of balances and public variables to hold token information.is a fundamental Ethereum token known as "Bitcoin Cash" and denoted by the sign "BCH". Token balance tracking for Ethereum addresses is also included, along with the ability to issue and burn tokens. A total of 0 tokens are initially available.

### The contract includes the following key features:

** Token Details:**
-tokenName: Public variable storing the name of the token, "Bitcoin Cash".
-tokenAbbrv: Public variable storing the token's abbreviation, "BCH".
-totalSupply: Public variable that tracks the total supply of the token, initially set to 0.

** Balances Mapping:**
-balances: A mapping that associates each address with its respective token balance.

 **Mint Function:**
-mint(address to, uint256 amount): Allows the creation of new tokens. Increases the totalSupply by the specified amount and credits the amount to the balance of the to address.

 **Burn Function:
**
-burn(uint256 amount): Allows the destruction of existing tokens. Decreases the totalSupply by the specified amount and debits the amount from the balance of from msg.sender, provided that the address has enough tokens to burn.

This program provides a foundational example of a simple token contract on the Ethereum blockchain, showcasing fundamental Solidity concepts and contract interactions.

# Getting Started

To run and interact with this program, you can use Remix, an online Solidity Integrated Development Environment (IDE). 
Here are the steps to get started:

# Execution Instructions

To deploy and interact with the "Bitcoin Cash" contract using Remix, follow these steps:

## Step-by-Step Instructions

1. Go to the Remix Website:
   => Open https://remix.ethereum.org/
   
2. Create a New File:

   => Click on the "+" icon in the left-hand sidebar.
   => Name the file ETH Proof/project.sol.
   
3. Copy and Paste the Solidity Code:

   =>Copy the Solidity code provided link : https://github.com/Sourov2002t/ETH_Project/blob/main/Token.sol which is visible on github page.
   =>Paste it into the newly created BifrostToken.sol file in Remix.
   
4. Compile the Code:

   => Click on the "Solidity Compiler" tab in the left-hand sidebar.
   => Ensure the compiler version is set to 0.8.9 (or another compatible version).
   =>Click on the "Compile project.sol" button.
   
5. Deploy the Contract:

   =>Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
   =>Ensure the environment is set to "Remix VM (London)" or a suitable network.
   =>Select the Bitcoin Cash contract from the dropdown menu.
   =>Click on the "Deploy" button.
   
6. Interact with the Contract:

  # Mint Tokens:
      =>In the deployed contract section, find the mint function.
      =>Enter the recipient's address and the amount of tokens to mint.
      =>Click on the transact button to mint tokens.
      
  # Burn Tokens:
       =>Find the burn function.
       =>Enter the amount to burn.
       =>Click on the transact button to burn tokens.
       
7. Check Balances:

    => Enter an address into the balances function and click on the call button to see the balance.
   
8> View Token Details:

 => Click on the tokenName, tokenAbbrv, and totalSupply buttons to display their values.
 
By following these instructions, you can successfully deploy and interact with the "Bitcoin Cash" contract on the Ethereum blockchain using Remix.

# Authors
 => Sourov Kumar Nandi
 
   Github  : https://github.com/Sourov2002t 
     
   LinkeIn : https://www.linkedin.com/in/sourov-kumar-nandi-77292924b
# License 
  This project is licensed under the MIT License - see the link ( https://github.com/Sourov2002t/ETH_Project/blob/main/LICENSE ) for details.

