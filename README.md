# contract
This is a simple implementation of a token on the Ethereum blockchain with minting and burning functionalities.

Features:
Token Details:

Name: Try
Symbol: T
Initial Total Supply: 0
Mapping: Tracks the balance of each address.

Mint Function:

Adds new tokens to a specified address.
Increases the total supply.
Burn Function:

Destroys tokens from a specified address if the balance is sufficient.
Decreases the total supply.
Functions:
mint(address _add, uint _v): Mints _v tokens to the address _add.
burn(address _add, uint _v): Burns _v tokens from the address _add if the balance allows.
