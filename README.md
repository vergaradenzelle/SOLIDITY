# MyToken

This is a simple Ethereum smart contract written in Solidity for a token called DENZELLE (DEN).

## Overview

This contract provides basic functionalities for managing the DENZELLE token. It allows minting new tokens and burning existing ones.

## Contract Details

- **Token Name**: DENZELLE
- **Token Abbreviation**: DEN
- **Total Supply**: 0 (initially)

## Public Variables

- `tokenName`: A public variable representing the name of the token.
- `tokenAbbrv`: A public variable representing the abbreviation of the token.
- `totalSupply`: A public variable representing the total supply of the token.

## Mappings

- `balances`: A mapping that maps addresses to their respective token balances.

## Functions

### `mint`

This function is used to mint new tokens and assign them to a specified address.

#### Parameters
- `_address`: The address to which the minted tokens will be assigned.
- `_value`: The amount of tokens to mint.

### `burn`

This function is used to burn (destroy) existing tokens from a specified address.

#### Parameters
- `_address`: The address from which tokens will be burned.
- `_value`: The amount of tokens to burn.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

