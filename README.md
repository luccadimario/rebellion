# Rebellion

A fully functional peer-to-peer blockchain implementation in Go with digital signatures, transactions, and proof-of-work consensus.

**Token Symbol:** RBL  
**Tagline:** Decentralized. Distributed. Revolutionary.

## Features

- **Proof of Work Mining** - Difficulty-based mining with configurable difficulty
- **Digital Signatures** - RSA-based transaction signing and verification
- **P2P Networking** - Multi-node network with automatic blockchain synchronization
- **Transactions** - Full transaction support with sender, recipient, and amount
- **Wallets** - RSA key pair generation for signing transactions
- **REST API** - HTTP endpoints for mining, viewing blockchain, and checking status

## Quick Start

### Prerequisites
- Go 1.16+

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/myblockchain.git
cd myblockchain
go run blockchain.go network.go api.go wallet.go transaction.go

