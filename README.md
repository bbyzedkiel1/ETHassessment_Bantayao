# MyToken Solidity Smart Contract
The objective of this contract is to be submitted for the ETH PROOF Beginner course assessment. This will show how a cryptocurrency token works.

# Description
This smart contract represents a basic token called "MyToken" which demonstrates how cryptocurrency token burning and minting is done.

# Content Overview
1. **Public Variables**: The contract includes public variables for storing token details:
    **tokenName**: Represents the full name of the token ("MARK" in this case).
    **tokenAbbrv**: Represents the abbreviation or symbol for the token ("MRK" in this case).
    **totalSupply**: Represents the total supply of tokens, initially set to 0.

2. **Mapping**: The contract defines a mapping named balances to keep track of token balances for each address. It maps addresses to the number of tokens they hold.

3. **Mint Function**: New tokens can be made using the mint function. It requires two parameters: a value (_value) and an address (_address). When called, it adds the specified amount to the address' balance and increases the overall supply by that amount.

4. **Burn Function**: The burning of tokens is made possible through the burn function. Additionally, it requires two parameters: a value (_value) and an address (_address). The function reduces the overall supply and subtracts the specified amount from the address' balance if the balance is sufficient.

# Getting Started
1. Open the source code in REMIX IDE.
2. Compile myToken.sol.
3. Use the Deploy & Run Transactions tab.
4. Now use your account address when burning or minting tokens.

# Author
Mark Yohann J. Bantayao

