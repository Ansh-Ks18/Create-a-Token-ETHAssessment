# CustomToken Smart Contract

## Project Title
CustomToken Smart Contract

## Simple Overview
A basic Ethereum smart contract that implements a custom token with minting and burning functionalities.

## Description
The CustomToken smart contract is designed to manage a simple ERC-20-like token named `ANSHU` with the abbreviation `AK`. It includes functions to mint new tokens and burn existing tokens, ensuring proper balance management. This contract can be used as a foundation for creating custom tokens on the Ethereum blockchain.

## Getting Started

### Installing

#### How/where to download your program
You can copy the contract code from the `Create-token` file in this repository.

#### Any modifications needed to be made to files/folders
No modifications are necessary. You can use the contract as is, but you are free to change the token name, abbreviation, or other parameters as per your requirements.

### Executing program

#### How to run the program

1. **Set Up Your Development Environment**:
    - Use [Remix IDE] https://remix.ethereum.org/ or any other Solidity development environment.
    
2. **Copy the Contract Code**:
    - Copy the code from `Create-token`.

3. **Compile the Contract**:
    - Paste the copied code into your Solidity file in Remix IDE.
    - Click on the "Solidity Compiler" tab and compile the contract.

4. **Deploy the Contract**:
    - Go to the "Deploy & Run Transactions" tab.
    - Select the desired environment (e.g., JavaScript VM, Injected Web3 for MetaMask).
    - Click "Deploy" to deploy the contract.

#### Step-by-step bullets

- **Mint Tokens**:
    ```solidity
    customTokenInstance.mint(0xYourAddressHere, 100);
    ```
    This command mints 100 tokens to the specified address.

- **Burn Tokens**:
    ```solidity
    customTokenInstance.burn(0xYourAddressHere, 50);
    ```
    This command burns 50 tokens from the specified address, provided the address has enough tokens.

### Help
For common problems or issues, ensure:

- You have sufficient balance for the burn function.
- The address used in minting and burning functions is correct.

If the contract fails to deploy, verify your Solidity version and ensure compatibility with the compiler settings.

## Authors

- **Anshu Kumar** - @AnshuKumar

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

---

For more information, please refer to the [Solidity Documentation](https://docs.soliditylang.org/).
```

This `README.md` follows the specified format and provides detailed instructions for downloading, installing, and using the CustomToken smart contract.
