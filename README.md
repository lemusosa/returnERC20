# returnERC20

A contract to return erroneously sent ERC20 tokens back to sender.

## Use-case

Sometimes users interact with a smart contract or dapp by sending the wrong ERC20 by mistake. This contract aims to help recover Any ERC20 token
from a smart contract provided the contract owner is still accessible an/or ethical.

## Use

1. This contract could be used as a library before instantiating a new smart contract.

2. For existing contracts this smart contract needs to be added to the approved list so that this contract can transfer the ERC20 tokens on
 behalf of the owner's smart contract.
 
3. You can interatc with the live contract to apporve this address to spend on the contracts behalf so it can
 
## Improvements

