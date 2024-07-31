# BLOCKCHAIN-FOR-MEDICAL-VERIFICATION

#Project Overview

This project aims to revolutionize the way medical records are stored and accessed by leveraging blockchain technology. By storing medical records on a blockchain, patients have full control over their data, ensuring both security and accessibility. Patients can set passwords to protect their records and grant access to doctors when necessary. This system saves testing time and allows doctors to make informed decisions quickly based on the patient's medical history.
Features

    Secure Storage: Medical records are securely stored on the blockchain, ensuring data integrity and protection against tampering.
    Patient Control: Patients have full control over their medical records and can set passwords to protect their data.
    Easy Access: Patients can grant access to their records to any doctor, facilitating quicker diagnosis and treatment.
    Efficiency: By accessing a patient’s medical history, doctors can avoid redundant tests and provide timely and accurate medical care.

#Technology Stack

    Blockchain Platform: Ethereum / Hyperledger / Other
    Smart Contracts: Solidity / Chaincode / Other
    Frontend: React / Angular / Other
    Backend: Node.js / Express / Other
    Database: IPFS / Other distributed storage solutions
    Authentication: OAuth / JWT / Other

#Prerequisites

    Node.js
    NPM or Yarn
    Truffle (for Ethereum) or relevant tools for chosen blockchain platform
    Metamask or other Ethereum wallet (if using Ethereum)
    Docker (for running blockchain nodes locally)

Getting Started
Clone the Repository

bash

git clone https://github.com/yourusername/blockchain-medical-verification.git
cd blockchain-medical-verification

Install Dependencies

bash

npm install

Setup Blockchain Network

Depending on the blockchain platform chosen, follow the respective setup instructions:
For Ethereum:

    Install Truffle and Ganache:

    bash

npm install -g truffle ganache-cli

Start Ganache:

bash

ganache-cli

Compile and Deploy Contracts:

bash

    truffle compile
    truffle migrate

Running the Application

    Start the backend server:

    bash

npm run start:backend

Start the frontend application:

bash

    npm run start:frontend

Usage

    Register as a Patient: Patients can sign up, set a password, and upload their medical records.
    Grant Access: Patients can grant access to their records to doctors by providing a secure token.
    Access Records: Doctors can access the patient's records with the token, allowing them to view the patient’s medical history.

Security

    Encryption: All medical records are encrypted before being stored on the blockchain.
    Access Control: Patients control who can access their records by generating and sharing access tokens.
    Immutable Records: Once stored on the blockchain, records cannot be altered or deleted, ensuring data integrity.

