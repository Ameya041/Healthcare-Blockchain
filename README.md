# Healthcare Blockchain Application

A decentralized application (DApp) for managing patient medical records on the Ethereum blockchain, providing secure and immutable health data storage.
![Screenshot 2025-04-16 232310](https://github.com/user-attachments/assets/85fcf3ec-0d07-422e-b546-cd3e7f23bd0c)
![Screenshot 2025-04-16 232325](https://github.com/user-attachments/assets/846c7522-22a6-40c2-9f0d-eedd270f4035)


## Features

- **Secure Medical Records**: Store patient diagnoses and treatments on the blockchain
- **Access Control**: Only authorized healthcare providers can add/view records
- **Ownership Management**: Contract owner can authorize new providers
- **Transparent History**: All records are timestamped and immutable
- **Patient Privacy**: Records accessed only with proper patient ID

## Technologies Used

- **Frontend**: React.js, Ethers.js
- **Smart Contracts**: Solidity
- **Blockchain**: Ethereum (testnet/local)
- **Wallet Integration**: MetaMask

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MetaMask browser extension
- Test ETH (for testnet deployment)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ameya041/Healthcare-Blockchain.git
cd Healthcare-Blockchain
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

### Smart Contract Deployment

1. Compile and deploy `healthcare.sol` using Remix IDE or Hardhat
2. Update the contract address in `Healthcare.js`

## Usage

1. Connect your MetaMask wallet
2. As contract owner:
   - Authorize healthcare providers
3. As authorized provider:
   - Add new patient records
   - View existing records by patient ID

## Project Structure

```
Healthcare-Blockchain/
├── public/              # Static files
├── src/
│   ├── App.js           # Main application component
│   ├── Healthcare.js    # Blockchain interaction logic
│   ├── App.css          # Styling
│   └── ...             
├── healthcare.sol       # Smart contract code
├── package.json         # Project dependencies
└── README.md            # This file
```

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/Ameya041/Healthcare-Blockchain](https://github.com/Ameya041/Healthcare-Blockchain)
```
