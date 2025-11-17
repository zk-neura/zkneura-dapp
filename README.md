# ZK-Neura dApp (Beta)

ZK-Neura is a privacy-preserving health intelligence application built on Solana.  
It enables users to manage health records locally, perform private AI-assisted health analysis, and generate Zero-Knowledge Proofs for secure, verifiable interactions without exposing sensitive data.

This repository contains the official ZK-Neura frontend application.

---

## Overview

- Local-first health records tied to the user's Solana wallet  
- AI Health Check for private symptom analysis  
- Zero-Knowledge proof generation (commitment + nullifier)  
- Privacy-preserving verification workflows  
- Fast, responsive UI using modern Next.js  
- No centralized data storage

---

## Features

- Wallet authentication (Phantom, Solflare, Backpack)
- Local encrypted record storage
- AI-based health assessment with no data retention
- Proof Vault for commitment & nullifier management
- Client-side cryptography (SHA-256, AES-GCM)
- Works on web and mobile browsers

---

## Technology Stack

- Next.js 16  
- React 19  
- TailwindCSS v4  
- shadcn/ui  
- Zustand  
- Zod  
- WebCrypto API  
- Solana Web3.js  
- Vercel AI Gateway → GPT-4o-mini  

---

## Getting Started

### 1. Clone

```bash
git clone https://github.com/zk-neura/zkneura-dapp
cd zkneura-dapp
