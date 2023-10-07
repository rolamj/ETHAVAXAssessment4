# Degen-Token-ERC-20-Metacrafters
This is a ERC20 token deployed on the Avalanche Fuji Testnet with a lot of functionalities, designed for gaming purposes on the Avalanche Fuji Test Network, made for Eth + Avax Intermediate Assesment 4 on the Metacrafters learning platform.

## Description

This program is a ERC20 token deployed on Avalanche Fuji Testnet and written in Solidity, a programming language used for developing smart contracts on the blockchain. 
The contract details are listed below :-

- Token Name: Degen 
- Token Symbol: DGN
- Decimals: 10
- Total Supply: 0 (initialized value)

The smart contract has the following functions like  'balanceOf', 'transfer', 'transferFrom' and 'approve'. It also contains some extra functionalities for minting ,burning tokens and add new nft accessories for the redeem section.

Only contract owner is able to mint tokens and create new nfts . Other users can interact with the contract by burning tokens, transferring tokens, approving token transfers on their behalf, checking their balance.



## Getting Started

### Functionalities

Use the 'mint' function (only owner) to mint new DGN tokens.

Use the 'storeNftAccessory' function (only owner) to add new NFT items for redemption.

Use the 'balanceOf' function to check the token balance of a specific address.

Use the 'transfer' function to send DEGEN tokens from your address to another address.

Use the 'approve' function to allow another address to spend a specific amount of DEGEN tokens on your behalf.

Use the 'transferFrom' function to transfer DEGEN tokens on behalf of another address.

Use the 'burn' function to burn DEGEN tokens.

Use the 'redeem' function to redeem DEGEN tokens for NFTs.

Using 'symbol' you can get the abbreviation of the token's name.

Using 'name' you can know the name of the token.

Using 'totalSupply' you can know the total amount of tokens present.

Using 'decimals' you can know the total amount of decimal places present.

Using 'owner' you can know the address of the owner.


### Executing program

(0) Make sure you are connected to the Avalanche Fuji Testnet in your Metamaska and have some test Avax.

(1) To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

(2) Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the code from token.sol file into your file:

(3) To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to latest solidity version (or another compatible version), and then click on the "Compile" button.

(4) Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the your contract from the dropdown menu, and then click on the "Deploy" button.

(5) In the "At Address" input field, enter the contract address : 0x64A53976712aa7e73a7B87239e27DAbFEE71fc2a .

(6) Once the contract is deployed, you can interact with it by calling the mint, burn function, transfer and much more.

## Authors

Tanishq

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
