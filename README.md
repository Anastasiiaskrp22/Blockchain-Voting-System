# ⛓️ Simple Blockchain Voting System – Python Implementation

## 🎯 Purpose

This project demonstrates a basic blockchain system built in Python for recording votes in a tamper-proof and verifiable way. Each vote is treated as a block in the chain, ensuring integrity through hashing and chain validation.

The project was developed as an educational exercise to understand how blockchain technology works under the hood — without using any external libraries or frameworks.

---

## 🛠️ Tech Stack

- Python 3
- Jupyter Notebook
- hashlib (SHA256)

---

## ⚙️ Features

- 🧱 Block creation with automatic hash calculation
- 🔒 Data integrity using SHA256
- 🔗 Chain linking with `previous_hash`
- ✅ Chain validation function 
- 🗳️ Custom voting data input 
- 📄 Fully documented, step-by-step logic in Jupyter Notebook

---

## ▶️ How It Works

1. A new vote is entered (e.g., candidate selection).
2. A block is created, hashed, and appended to the chain.
3. Each block stores:
   - Voter name (or ID)
   - Voted candidate
   - Timestamp
   - Hash and previous hash
4. A chain validation function ensures no block has been tampered with.

---

## 📸 Example Output

```json
{
  "index": 3,
  "timestamp": "2025-08-02 14:23:54",
  "data": {
    "voter": "Alice",
    "vote": "Candidate A"
  },
  "hash": "003f5af9...",
  "previous_hash": "00a9e37..."
}
