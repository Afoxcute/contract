# Smart Contract for Rock-Paper-Sissors on CoreDAO testnet

This is a decentralized Rock-Paper-Scissors Smart contract built on the CoreDao testnet network. The Smart Contract acts as the intermediary that allows users to create and join games, track their move history, and view past game results, all while ensuring transparency and fairness through blockchain technology.

Try running some of the following tasks:

## Getting Started

To get started with the contract, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/contract.git
   cd contracts
   Edit hardhat.config.ts and change the URL(which is the endpoint URL) as desired.
   ```

2. Install the dependencies:
   ```bash
   npm install or yarn install
   create .env file and add YOUR_PRIVATE_KEY to it
   ```

3. Compile & Deploy Contract:
   ```bash
   npx hardhat compile
   npx hardhat run ./scripts/deploy.js
   ```

4. Open [[http://localhost:3000](https://scan.test.btcs.network/address/0x7296c77Edd04092Fd6a8117c7f797E0680d97fa1)](https://scan.test.btcs.network/address/0x7296c77Edd04092Fd6a8117c7f797E0680d97fa1) in your browser to see the Contract on-chain.
