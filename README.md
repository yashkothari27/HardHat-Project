# ERC20 Token Project with Solidity & HardHat

This project is a simple implementation of an ERC20 token using Solidity and managed with HardHat. The ERC20 token standard allows for the creation of fungible tokens on the Ethereum blockchain.

## Prerequisites

Before getting started, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- HardHat

## Installation

1. Clone this repository:

    ```bash
    git clone <repository_url>
    ```

2. Install dependencies:

    ```bash
    cd <project_folder>
    npm install
    ```

## Project Structure

- `contracts/`: Contains Solidity smart contracts.
- `scripts/`: Includes scripts to interact with the smart contracts.
- `tests/`: Holds tests for the smart contracts.
- `hardhat.config.js`: Configuration for HardHat tasks and networks.
- `README.md`: This file.

## Usage

1. Compile the smart contracts:

    ```bash
    npx hardhat compile
    ```

2. Run tests:

    ```bash
    npx hardhat test
    ```

3. Deploy the contracts to a local network:

    ```bash
    npx hardhat node
    npx hardhat run scripts/deploy.js --network localhost
    ```

## Customization

- Adjust contract parameters and functionality in the `contracts/` directory.
- Modify deployment scripts in the `scripts/` directory for specific deployment needs.

## Contributing

Feel free to contribute by opening issues or pull requests. Contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).

