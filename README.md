# Try Token (T)

This is a simple implementation of a token on the Ethereum blockchain with minting and burning functionalities.

## Token Details

- **Name**: Try
- **Symbol**: T
- **Initial Total Supply**: 0

The token uses a mapping to track the balance of each address.

## Features

### Mint Function

- Adds new tokens to a specified address.
- Increases the total supply.

### Burn Function

- Destroys tokens from a specified address if the balance is sufficient.
- Decreases the total supply.

## Functions

### `mint(address _add, uint _v)`

Mints `_v` tokens to the address `_add`.

### `burn(address _add, uint _v)`

Burns `_v` tokens from the address `_add` if the balance allows.

## Usage

1. **Minting Tokens**
    ```solidity
    function mint(address _add, uint _v) public {
        // Add _v tokens to the balance of _add
        // Increase the total supply by _v
    }
    ```

2. **Burning Tokens**
    ```solidity
    function burn(address _add, uint _v) public {
        // Ensure the balance of _add is sufficient
        // Subtract _v tokens from the balance of _add
        // Decrease the total supply by _v
    }
    ```
