# 🏡 Blockchain Land Registry

A **decentralized land registry system** built on **Ethereum blockchain** using **Solidity, Truffle, Ganache, Web3.py, and Streamlit**.  
This project allows users to **register land, transfer ownership, and verify land details securely** on the blockchain.

---

## 🚀 Features
✅ Register new land parcels securely.  
✅ Transfer land ownership with blockchain verification.  
✅ Fetch land details instantly.  
✅ Decentralized and tamper-proof record system.  

---

## 🛠 Tech Stack
- **Blockchain:** Ethereum, Solidity, Web3.js, Truffle, Ganache  
- **Backend:** Python, Web3.py  
- **Frontend:** Streamlit  

---

## 📦 Installation & Setup

### 1️⃣ **Install Dependencies**
Make sure you have **Node.js**, **Python**, and **Ganache** installed.

# Install Truffle globally
```bash
npm install -g truffle
```

# Install Python dependencies
```bash
pip install web3 streamlit
```

# Blockchain-Based Land Registry

## 🏗 Setup Guide

### 1️⃣ Start Ganache
Run Ganache on:
```
http://127.0.0.1:7545
```

### 2️⃣ Compile & Deploy Smart Contract
Run the following command to compile and deploy the smart contract:
```bash
truffle migrate --reset
```

### 3️⃣ Run the Streamlit App
Start the frontend by running:
```bash
streamlit run app.py
```

---

## 📜 Usage Guide

### ➤ Register a New Land Parcel
1. Select an Ethereum account (from Ganache).
2. Enter the Land ID, Location, and Area.
3. Click **"Register Land"** to store it on the blockchain.

### ➤ Transfer Land Ownership
1. Enter the **Land ID** to transfer.
2. Select a new owner from the available Ethereum accounts.
3. Click **"Transfer Ownership"** to update blockchain records.

### ➤ View Land Details
1. Enter the **Land ID** to check details.
2. Click **"Fetch Details"** to view registered information.

---

## 🛠 Troubleshooting

❌ **Web3 is not connected**  
✔ Ensure Ganache is running on port **7545**.

❌ **Smart contract not deployed**  
✔ Run `truffle migrate --reset` and restart the app.

❌ **Transaction failed (gas issue)**  
✔ Increase the gas limit in `backend.py` to **500000**.

---

## 🔗 References
- [Ethereum & Web3](https://ethereum.org)
- [Solidity Documentation](https://soliditylang.org)
- [Truffle Suite](https://trufflesuite.com)
- [Streamlit](https://streamlit.io)

---

## ✨ Future Improvements
🚀 **User Authentication with MetaMask**  
🚀 **NFT-based Land Titles**  
🚀 **Integration with IPFS for Land Documents**  

---

## 👨‍💻 Author
🔹 Subinesh  
📧 subinesh.b2c@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/subinesh-b-92125a323?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app ) | [GitHub](https://github.com/The-Whiz-Guy)

---

This **README** includes everything needed to install, run, and troubleshoot your project. 🚀  
Let me know if you need modifications! 😊
