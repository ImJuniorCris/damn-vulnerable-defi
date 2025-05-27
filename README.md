# DamnVulnerableDeFi

A set of smart contracts and challenges to learn and practice DeFi security vulnerabilities and exploit techniques.

## About

DamnVulnerableDeFi is an educational repository containing intentionally insecure DeFi smart contracts and CTF-style exercises for learning about common vulnerabilities in decentralized finance.

## Features

- Multiple DeFi challenges with increasing complexity
- Realistic smart contract vulnerabilities for hands-on learning
- Ready-to-use testing framework for local development
- Detailed solutions and explanations for each challenge

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Hardhat](https://hardhat.org/)

### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/TartarusDevtech/DamnVulnerableDeFi.git
   cd DamnVulnerableDeFi
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Compile contracts:
   ```bash
   npx hardhat compile
   ```

### Running the Challenges

Each challenge is located in the `contracts/` and `test/` directories. To run the tests:

```bash
npx hardhat test
```

Follow instructions in each challenge folder and the test files to attempt exploits.

## Contributing

Contributions, new challenges, and improvements are welcome! Please open an issue or pull request.

## License

This project is licensed under the MIT License.

## Disclaimer

This repository is for educational purposes only. Do not use these vulnerabilities in production or for malicious purposes.
