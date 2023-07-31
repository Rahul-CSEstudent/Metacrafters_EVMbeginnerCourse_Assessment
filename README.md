# MyToken - Simple Solidity Smart Contract for a Custom Token

## Description
MyToken is a simple Solidity smart contract that allows the creation and management of a custom token on the Ethereum blockchain. The contract includes functionalities for minting (creating) and burning (destroying) tokens, as well as keeping track of token balances for different addresses.

## Getting Started
### Installing
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Follow the instructions below.

### Executing Program
1. Copy the entire content of the MyToken.sol file into your Solidity development environment.
2. Compile the contract to check for any syntax errors or warnings.
3. Deploy the contract to an Ethereum testnet or the mainnet.
4. Once deployed, you can interact with the contract through the provided functions.

### Mint Function
The mint function allows you to create new tokens and assign them to a specific address. To use the mint function, provide the address you want to assign the tokens to and the number of tokens you want to create. The function will increase the total supply of tokens and update the balance of the provided address accordingly.

### Burn Function
The burn function is used to destroy tokens. To burn tokens, specify the address from which you want to deduct the tokens and the amount of tokens you want to destroy. The function will only proceed if the balance of the given address is greater than or equal to the specified amount. It will decrease the total supply and update the balance of the address accordingly.

## Help
In case you encounter any issues or have questions about the contract's functionalities, you can refer to the Solidity documentation or seek help from the Ethereum development community.

## Authors
Rahul B
@Rahul-CSEstudent

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
