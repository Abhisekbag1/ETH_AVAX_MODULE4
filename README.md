# ETH_AVAX_MODULE4_Project
# Degen Gaming ERC20 Token

This is a smart contract for the Degen Gaming ERC20 token deployed on the Avalanche network. The contract provides functionality for minting new tokens, transferring tokens, redeeming tokens for in-game items, checking token balances, and burning tokens.

## Contract Details

- Token Name: Degen Token
- Token Symbol: DEGEN

## Functionality

### Minting new tokens

The owner of the contract can mint new tokens by calling the `mint` function, specifying the recipient's address and the desired token amount.

### Transferring tokens

Players can transfer their tokens to others by calling the `transfer` function, specifying the recipient's address and the token amount to be transferred.

### Redeeming tokens

Players can redeem their tokens for in-game items in the in-game store by calling the `redeem` function and specifying the token amount to be redeemed. Additional logic for item redemption should be implemented in the contract.

### Checking token balance

Players can check their token balance at any time by calling the `balanceOf` function and providing their account address.

### Burning tokens

Anyone can burn their own tokens by calling the `burn` function and specifying the amount of tokens to be burned.

## Deployment

The contract has been deployed on the Avalanche network for Degen Gaming.

