
# Web3 Crowdfunding Project

This project is a decentralized crowdfunding platform built on Web3 technology. It leverages modern web development frameworks and libraries to create a seamless user experience.

## Tech Stack

- **JavaScript (JS)**: The primary programming language used for both frontend and backend development.
- **Web3.js**: A library to interact with the Ethereum blockchain.
- **Thirdweb**: A platform to manage and deploy smart contracts.
- **Hardhat**: A development environment for Ethereum software.
- **Next.js**: A React framework for server-side rendering and static site generation.
- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn
- Metamask (or any Ethereum wallet)

### Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/web3-crowdfunding.git
   cd web3-crowdfunding

Install dependencies:
sh
Copy code
npm install
# or
yarn install
Setting Up the Web3 Part
Navigate to the Web3 directory:

sh
Copy code
cd web3
Initialize Hardhat:

sh
Copy code
npx hardhat
Install required packages:

sh
Copy code
npm install @openzeppelin/contracts dotenv @nomiclabs/hardhat-ethers
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
Create a .env file and add your private key:

plaintext
Copy code
PRIVATE_KEY=your_private_key_here
Configure Hardhat:
Copy the hardhat.config.ts file from the repository or set up your own configuration.

Compile the smart contracts:

sh
Copy code
npx hardhat compile
Deploy the smart contracts:

sh
Copy code
npx hardhat run scripts/deploy.ts --network your_network
Setting Up the Frontend
Navigate to the frontend directory:

sh
Copy code
cd frontend
Install frontend dependencies:

sh
Copy code
npm install
# or
yarn install
Start the development server:

sh
Copy code
npm run dev
# or
yarn dev
Configuration
Tailwind CSS: Tailwind is already configured in the tailwind.config.js file. You can customize it as needed.
Thirdweb: Ensure your smart contracts are deployed and integrated with Thirdweb as per the documentation.
