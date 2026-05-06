# Useful contracts

These are contracts that are either part of the underlying protocol or
expected to be useful for multiple projects.


## StarkNet contracts

* StarkNet Core contract
    * Goerli: [0xde29d060D45901Fb19ED6C6e959EB22d8626708e](https://goerli.etherscan.io/address/0xde29d060D45901Fb19ED6C6e959EB22d8626708e)
    * Mainnet: [0xc662c410C0ECf747543f5bA90660f6ABeBD9C8c4](https://etherscan.io/address/0xc662c410C0ECf747543f5bA90660f6ABeBD9C8c4)

* Verifier
    * Goerli: [0x8f97970aC5a9aa8D130d35146F5b59c4aef57963](https://goerli.etherscan.io/address/0x8f97970aC5a9aa8D130d35146F5b59c4aef57963)
    * Mainnet: [0x47312450B3Ac8b5b8e247a6bB6d523e7605bDb60](https://etherscan.io/address/0x47312450B3Ac8b5b8e247a6bB6d523e7605bDb60)

* GpsStatementVerifier
    * Goerli: [0xb59d5f625b63fbb04134213a526aa3762555b853](https://goerli.etherscan.io/address/0xb59d5f625b63fbb04134213a526aa3762555b853)
    * Mainnet: [0x6cb3ee90c50a38a0e4662bb7e7e6e40b91361bf6](https://etherscan.io/address/0x6cb3ee90c50a38a0e4662bb7e7e6e40b91361bf6)

* MemoryPageFactRegistry
    * Goerli: [0xdc1534eeBF8CEEe76E31C98F5f5e0F9979476c87](https://goerli.etherscan.io/address/0xdc1534eebf8ceee76e31c98f5f5e0f9979476c87)
    * Mainnet: [0xfd14567eaf9ba941cb8c8a94eec14831ca7fd1b4](https://etherscan.io/address/0xfd14567eaf9ba941cb8c8a94eec14831ca7fd1b4)

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
