# Supplychain_Management_System
Creating Supply chain management System using blockchain technology for authentic supplies of medicines.

# Blockchain-Project

## Local Development setup

### Step 1

Open ganache UI/cli and configure truffle-config.js file.

### Step 2

Import the ganache local blockchain accounts in metamask using each account's private key

### Step 3

Clone the repo

```terminal
git clone https://github.com/iparthpawar/Supplychain_Management_System.git
cd .\Blockchain-Project\Supplychain-Medicine-blockchain
```

Install `node_modules` using `npm`

```terminal
npm install
```

### Step 4

Compile and deploy the smart contract

```terminal
npx truffle compile
npx truffle migrate
```

> NOTE: If you make changes in the smart contract you have to redeploy it using `npx truffle migrate --reset`

### Step 5

Install `node_modules` using `npm`

```terminal
cd client
npm install
```

### Step 6

Start the development server using `npm`

```terminal
npm start
```

