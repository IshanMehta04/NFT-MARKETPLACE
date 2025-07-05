
# 🖼️ NFT Marketplace

A decentralized NFT marketplace built with React, enabling users to mint, view, and interact with NFTs using Ethereum and Tezos blockchains. The platform integrates IPFS for secure decentralized storage and provides a clean UI for an intuitive user experience.

---

## ✨ Features

- 🧾 NFT minting and listing
- 🌐 Ethereum and Tezos blockchain integration
- 🗂️ Metadata upload via IPFS
- 🎨 Dynamic and clean UI with React & Tailwind CSS
- 🛠️ Web3 interactions through smart contracts
- 🔁 Real-time updates and smooth UX

---

## ⚙️ Tech Stack

- **Frontend:** React, Tailwind CSS
- **Blockchain:** Ethereum, Tezos
- **File Storage:** IPFS
- **Libraries & Tools:** Web3.js, Taquito, Axios

---

## 📂 Folder Structure

```
nft-marketplace/
├── backend/                # Blockchain and service logic
│   ├── TezosService.js
│   ├── ethereumService.js
│   └── index.js
├── public/                 # Public files
│   └── index.html
├── src/
│   ├── components/         # Reusable UI and functional components
│   ├── pages/              # Page-level components like Home and Marketplace
│   ├── services/           # Ethereum and Tezos interaction services
│   ├── styles/             # Global styles
│   ├── App.js
│   └── index.js
├── .gitignore
├── package.json
├── tailwind.config.js
└── README.md
```

---

## 🧑‍💻 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/nft-marketplace.git
cd nft-marketplace
```

### 2. Install dependencies
```bash
npm install
cd backend
npm install
```

### 3. Start the development server
```bash
# Start backend (if needed)
node index.js

# In a new terminal, start frontend
npm start
```

App will run on: [http://localhost:3000](http://localhost:3000)

---

## 🌍 Live Demo

_Coming soon..._

---

## 📸 Screenshots

_Add UI screenshots here if available._

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📌 To-Do / Future Improvements

- Smart contract deployment to mainnet
- Wallet connection for Tezos
- Better NFT search/filter options
- Add user profile pages

