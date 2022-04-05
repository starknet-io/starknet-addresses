# Useful contracts

These are contracts that are either part of the underlying protocol or
expected to be useful for multiple projects.


## StarkNet contracts

* StarkNet Core contract
    * Goerli: [0xde29d060D45901Fb19ED6C6e959EB22d8626708e](https://goerli.etherscan.io/address/0xde29d060D45901Fb19ED6C6e959EB22d8626708e)
    * Mainnet: [0xc662c410C0ECf747543f5bA90660f6ABeBD9C8c4](https://etherscan.io/address/0xc662c410C0ECf747543f5bA90660f6ABeBD9C8c4)

* Verifier
    * Goerli: [0xAB43bA48c9edF4C2C4bB01237348D1D7B28ef168](https://goerli.etherscan.io/address/0xAB43bA48c9edF4C2C4bB01237348D1D7B28ef168)
    * Mainnet: [0x47312450B3Ac8b5b8e247a6bB6d523e7605bDb60](https://etherscan.io/address/0x47312450B3Ac8b5b8e247a6bB6d523e7605bDb60)

## Bridged Tokens

Under the bridged token addresses folders you will find Json files (one per network) containing the
addresses of the tokens currently bridged to StarkNet. Each token has the following parameters:

* Name: name of the token
* Symbol: token symbol
* Decimals: number of decimals used to get the user representation
* l1_token_address: address of the L1 ERC-20 contract
* l2_token_address: address of the L2 ERC-20 contract
* l1_bridge_address: address of the L1 bridge contract
* l2_bridge_address: address of the L2 bridge contract
