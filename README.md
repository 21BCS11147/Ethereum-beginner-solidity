# MetaCrafterToken

MyToken is an Ethereum token contract that allows the contract owner to mint tokens to a provided address, and users to burn and transfer tokens.

## Features

- Mint tokens to a specified address by the contract owner.
- Burn tokens by any user.
- Transfer tokens between addresses.

## Prerequisites

- Remix-IDE

## Contract Details

- Name: setbyuser
- Symbol: setbyuser
- Supply: setbyuser

### Functions

#### `mint(address account, uint256 amount)`

Mints new tokens and assigns them to the specified account.

- `account`: The address to which the tokens will be minted.
- `amount`: The number of tokens to mint.

This function can only be called by the contract owner.

#### `burn(uint256 amount)`

Burns the specified number of tokens from the caller's account.

- `amount`: The number of tokens to burn.


## License

MIT License-see details [here]()

