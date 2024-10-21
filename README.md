
# TransCrypt

Ensuring a Safe Environment for Every Type of Transaction


## Project Description

TransCrypt is a decentralized escrow platform built on the Azle TypeScript framework, integrating secure fund management for various types of transactions. It allows users to create or join transactions, set milestones, and utilize an escrow system to protect payments until all agreed terms are met.
## 🧩 Features:

- Account Creation & Authentication: Secure user signup and login processes.
- KYC Process: User document uploads.
- Dashboard: Displays wallet balance, transaction history, and ongoing transactions.
- Wallet Management: Add/reduce funds and track transaction history.
- Transaction Management: Users can create or join transactions, define milestones, and release payments based on milestones.
- Escrow Holding: Funds are securely held in escrow and released upon approval.


## Get started with one click:
### Locally:

Make sure you have you have the latest version of Docker (e.g. >25) and VS Code installed and running, then click the button below

[![Open locally in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/bowtsogakow/ICPHackaton2024-FisherBytes)

### In your browser:

In Gitpod 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/bowtsogakow/ICPHackaton2024-FisherBytes)

## 🚀 Develop

When the editor opened, run the following commands to start a local ICP node and deploy the canister smart contract:

```bash
dfx start --clean # Start a local ICP node
# In a new terminal window:
dfx deploy # Deploy smart contract locally
```

The smart contract will be reachable under `http://bkyz2-fmaaa-aaaaa-qaaaq-cai.localhost:4943`.


## 📋 Setup Guide:
### Here is a more detailed setup flow in case the first one don't work

    1. Get the docker container from this repository:
        https://github.com/ICPHubPH/azle-react.git
    2. Setup the docker container provided by (make sure that you have installed docker and vscode on your desktop).
    3. Change the git origin to this reporsitory:
        https://github.com/bowtsogakow/ICPHackaton2024-FisherBytes.git
    4. Pull files on main branch.
    5. On terminal, run the command (dfx start --clean).
    6. On a separate terminal run (dfx deploy).
    7. To initiate an escrow wallet type this curl command in terminal:
    curl -X POST http://bkyz2-fmaaa-aaaaa-qaaaq-cai.localhost:4943/wallet/create -H 'content-type: application/json' -d '{"owner_username" : "escrow", "type" : "escrow" }'


## 🛠️ Technology Stack

- [Azle CDK](https://demergent-labs.github.io/azle/): the Canister Development Kit for JS/TS
- [Vite](https://vitejs.dev/): high-performance tooling for front-end web development
- [React](https://reactjs.org/): a component-based UI library
- [TypeScript](https://www.typescriptlang.org/): JavaScript extended with syntax for types

## 📚 Prerequisites
### Before you begin, ensure you have the following installed:

Node.js (v14 or higher),
Docker (for containerized development),
TypeScript (v4 or higher),
Azle Framework (latest version),
Vite (for frontend development),
TypeORM (for database entities)
## 👨🏻‍💻Team Members

  ### Project Leader:
   Garabilez, Mark Leonard S.
  ### Backend Developers:
   De Leon, Zymon C.

   Caparas, Willfred Ivan L.
  ### Frontend Developers:
   Arandia, Justine M.

   Crisostomo, Marc Ashley F.
## 💻 Demo

Insert gif or link to demo


## ⚡️ Github Repository:
https://github.com/bowtsogakow/ICPHackaton2024-FisherBytes.git
