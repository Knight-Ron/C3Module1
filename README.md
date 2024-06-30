# Error Handling in Solidity Smart Contract

This Solidity smart contract demonstrates the usage of error handling mechanisms like `require`, `revert`, and `assert`, along with custom errors in the Ethereum blockchain.

## Description

The `Error` contract includes functions to show how different error handling methods are implemented in Solidity:
- `testRequire`: Uses `require` to validate input conditions.
- `testRevert`: Uses `revert` to handle complex condition checks.
- `testAssert`: Uses `assert` to check for internal errors and invariants.
- `testCustomError`: Implements a custom error for more detailed error handling.

These methods ensure that your smart contract behaves correctly under various conditions and provides meaningful error messages when something goes wrong.

## Getting Started

### Installing

1. **Download the Contract:**
   - Copy the Solidity code from the `Error.sol` file provided above.
   - Save it in your project directory as `Error.sol`.

2. **Install Remix IDE:**
   - You can use Remix IDE, an online tool for writing, compiling, and deploying Solidity smart contracts. Navigate to [Remix IDE](https://remix.ethereum.org/) in your web browser.

### Executing program

1. **Compile the Contract:**
   - Open Remix IDE.
   - Create a new file named `Error.sol`.
   - Paste the contract code into this file.
   - Select the appropriate compiler version (`0.8.26`) from the compiler tab.
   - Click on the "Compile" button.

2. **Deploy the Contract:**
   - Switch to the "Deploy & Run Transactions" tab.
   - Ensure your Metamask wallet 🦊 is connected to Remix.
   - Select the environment (e.g., JavaScript VM, Injected Web3 for using Metamask).
   - Click on "Deploy".

3. **Interact with the Contract:**
   - Once deployed, you can interact with the contract functions (`testRequire`, `testRevert`, `testAssert`, `testCustomError`) directly from the Remix interface.
   - Enter appropriate inputs to test the functions and observe how different error handling mechanisms work.

### Example Usage

#### Compile and Deploy:
```solidity
// Use Remix IDE to compile and deploy the contract
