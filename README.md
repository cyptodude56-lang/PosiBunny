# 🐰 PosiBunny

A Solana devnet memecoin built from scratch — demonstrating real-world token creation, keypair management, and blockchain deployment on the Solana network.

---

## 🚀 What This Project Demonstrates

- ✅ Solana token creation on Devnet
- ✅ Keypair generation & secure key management
- ✅ Docker containerization of a blockchain project
- ✅ Clean project structure with security best practices (.gitignore for private keys)

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Solana Web3.js | Blockchain interaction |
| Node.js v25 | Runtime |
| Docker | Containerization |
| Solana Devnet | Test network |

## ⚙️ Setup & Run

1. Clone the repo
```bash
   git clone https://github.com/cyptodude56-lang/PosiBunny.git
   cd PosiBunny
```

2. Add your own Solana keypair JSON files (not included for security)

3. Run with Docker
```bash
   docker build -t posibunny .
   docker run posibunny
```

## 🔐 Security

Private keypairs are excluded via `.gitignore` and should never be committed to any repository. Generate your own using the Solana CLI:
```bash
solana-keygen new --outfile my-keypair.json
```

## 🌐 Network

Currently deployed on **Solana Devnet** for testing purposes.

## 👤 Author

**Crypto Dude** — [@cyptodude56-lang](https://github.com/cyptodude56-lang)

> Open to collaboration, freelance blockchain work, and Web3 opportunities.

---

⭐ If you found this useful, consider starring the repo!
