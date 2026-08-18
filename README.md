# REU Alien NFT Collection

A single-page Web3 decentralized application (dApp) for minting **REU Alien NFTs** on the Ethereum network using MetaMask and IPFS.

---

## Project Details

* **Token Contract Address:** [`0xb8eF45d272D357Ff694dE43E5Fa1c5D763B72d7C`](https://sepolia.etherscan.io/address/0xb8eF45d272D357Ff694dE43E5Fa1c5D763B72d7C)
* **Contract Deployer / Wallet:** `0x18788A7b49FB126B11102C61988b1068BDaFcA7f`
* **Metadata IPFS CID:** `bafybeifrff6yjyf7esz4rsfusasdjbxmckfm3a3ch7qvbm756usovunoze`
* **IPFS Gateway Link:** [ipfs://bafybeifrff6yjyf7esz4rsfusasdjbxmckfm3a3ch7qvbm756usovunoze](https://ipfs.io/ipfs/bafybeifrff6yjyf7esz4rsfusasdjbxmckfm3a3ch7qvbm756usovunoze)

---

## Development & Creation Process

### Step 1: Pinata IPFS Asset Upload
1. Uploaded the original NFT artwork file (`alien.png`) to **Pinata.cloud**.
2. Generated the initial Image IPFS CID.

### Step 2: Metadata JSON Construction
1. Created a local file named `metadata.json` referencing the uploaded image CID:
   ```json
   {
     "name": "REU Alien #1",
     "description": "Official REU Alien NFT Collection",
     "image": "ipfs://YOUR_IMAGE_CID_HERE",
     "attributes": [
       {
         "trait_type": "Species",
         "value": "Alien"
       },
       {
         "trait_type": "Collection",
         "value": "REU"
       }
     ]
   }

   # REU Alien NFT Collection

A lightweight, single-page Web3 decentralized application (dApp) for minting **REU Alien NFTs** on the Ethereum network using MetaMask and IPFS.

---

## 🚀 How to Mint

1. Open the live site hosted via **GitHub Pages**.
2. Click **Connect MetaMask** and approve the connection popup.
3. Paste your Pinata CID (or use the default CID provided above).
4. Click **Mint REU NFT** and confirm the transaction in MetaMask.

---

## 🛠️ Built With

* **HTML5 / CSS3** (Vanilla Glassmorphism UI)
* **JavaScript (ES6+)**
* **Ethers.js v5** (Web3 Provider & Contract Interactions)
* **IPFS / Pinata** (Decentralized Asset & Metadata Storage)
* **GitHub Pages** (Free Static Hosting)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
