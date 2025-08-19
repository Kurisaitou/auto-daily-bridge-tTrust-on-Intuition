# Auto Bridge Bot for tTrust to Base Sepolia on Intuition

<img width="1705" height="513" alt="image" src="https://github.com/user-attachments/assets/584b70a4-ab9c-40e0-9381-e3641c1eb00b" />

## 🚀 Features
- Daily automated Bridge on Intuition

- tTrust ↔ Base Sepolia Bridge using on-chain in Intuition Testnet

- Dynamic delay and transaction range per day (configured via .env)

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Kurisaitou/auto-daily-bridge-tTrust-on-Intuition.git
```
```bash
cd auto-daily-bridge-tTrust-on-Intuition
```
```bash
npm install
```

## ⚙️ Environment Setup
Create a .env file in the project root:
```bash
nano .env
```
Fill in your wallet details and configure your preferred settings:
```bash
PRIVATE_KEY=your_privatekey
RPC_URL=https://testnet.rpc.intuition.systems/http
DEST=your_address

# daily quota
TX_MIN_PER_DAY=3
TX_MAX_PER_DAY=6

# per-tx delay (seconds)
DELAY_MIN_SEC=60
DELAY_MAX_SEC=180

# amount range (in tTRUST / ETH units)
AMOUNT_MIN=0.0001
AMOUNT_MAX=0.001
```

## ▶️ Running the Bot
To start the bot:
```bash
node index.js
```

## 🔖 Tags
#Intuition #airdrop #swap #bot #crypto #web3 #automation #trading #dex #tTrust #bridge #caldera
