# ERC20 Token Smart Contract

A simple and functional ERC20 token contract to demonstrate minting, burning, and transferring tokens. This project aims to provide a foundational understanding of ERC20 tokens and how to interact with them using HardHat or Remix.

## Description

This project involves writing a smart contract to create and manage an ERC20 token. The contract includes functions for minting new tokens by the contract owner, burning tokens by any token holder, and transferring tokens between addresses. Additionally, the contract owner has the ability to transfer ownership to another address. The project is deployed using HardHat or Remix, and a video walk-through is provided to explain the contract's functionality and interactions.

## Getting Started

### Installing

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```
## Executing Program

### Using HardHat

1. **Compile the Contract**
   ```bash
   npx hardhat compile
   ```
2. **Deploy the Contract**
   Create a deployment script `scripts/deploy.js`
   Run the deployment script:
   ```bash
   npx hardhat run scripts/deploy.js --network network_name
   ```

### Using Remix
1. **Open Remix IDE:** Navigate to Remix.
2. **Create a New File:** Create a new file and paste the contract code.
3. **Compile the Contract:** Use the Solidity compiler to compile the contract.
4. **Deploy the Contract:** Select the appropriate environment and deploy the contract.

## Help
For common issues, consider the following:
1. Ensure you have the correct version of Node.js installed.
2. Double-check the network configuration in HardHat.
3. Make sure your wallet is connected correctly in Remix.

If the program contains helper information, use:
  ```bash
   npx hardhat help
   ```
## Authors

Gaurav  
[@GauravHandle](https://www.linkedin.com/in/gaurav-kumar-18151819b/)

## License
