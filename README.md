# DegenToken

DegenToken is an ERC-20 token with additional features, including power-ups and burning capabilities. It is built on the Ethereum blockchain using Solidity.

## Features

1. **ERC-20 Standard**: Implements the standard ERC-20 interface for compatibility with other Ethereum tokens.

2. **Ownable Contract**: Utilizes the Ownable contract from OpenZeppelin, ensuring only the contract owner can perform certain operations.

3. **Burnable Tokens**: Inherits from ERC20Burnable, allowing token holders to burn their own tokens.

4. **Power-Ups**: Introduces a system of power-ups that users can purchase, each with a name, price, and duration.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Truffle](https://www.trufflesuite.com/truffle)
- [Ganache](https://www.trufflesuite.com/ganache) (for local development and testing)

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd degen-token
