# BlockCred: Decentralized Credential Verification Using Blockchain Technology

## 📄 Overview

**BlockCred** is a decentralized application designed to authenticate academic certificates using blockchain technology. By leveraging the immutable nature of blockchain, BlockCred ensures that issued certificates are tamper-proof and easily verifiable by employers, institutions, and other stakeholders.


## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

### 1. **Certificate Generation**
- **Template Uploader**: Upload custom certificate templates.
- **CSV Uploader**: Upload candidate data in bulk using CSV files.
- **Certificate Editor**:
  - Add customizable boxes for candidate information (e.g., name, registration number).
  - Drag and drop boxes for precise placement on the template.
  - Include a QR code box for blockchain hash storage.
  - Test certificate layouts before finalizing.
 ![image](https://github.com/user-attachments/assets/f003d5f7-d8e0-49a2-bb51-534bc4481e51)

## 🛠️ Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Blockchain**: Ethereum, Solidity
- **Smart Contracts**: Deployed using Truffle Suite
- **Storage**: IPFS (InterPlanetary File System) for storing certificate files
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: MongoDB
- **Bulk Certificate Generation**:
  - Automatically generate certificates with candidate data and QR codes.
  - Store candidate information securely on the blockchain.

### 2. **Certificate Validation**
- **Verify Certificate**:
  - Scan the QR code to retrieve the blockchain hash.
  - Verify the certificate authenticity through the blockchain.
  - Display candidate details if valid or indicate invalid certificates.
  ![image](https://github.com/user-attachments/assets/ac9f17e6-6963-400e-99ae-8f386ad5f9ef)
### 3. **Security**
- Employs blockchain technology for tamper-proof certificate validation.
- Uses smart contracts for storing certificate data securely.

## Technology Stack

### Frontend
- [React.js](https://reactjs.org/): For building a dynamic and interactive user interface.
- [Tailwind CSS](https://tailwindcss.com/): For responsive and modern styling.


## Backend
- [Flask](https://flask.palletsprojects.com/): For processing and API management.
- [Python Libraries](https://pypi.org/):
  - `pandas`: For handling CSV data.
  - `qrcode`: For generating QR codes.
  - `hashlib`: For generating unique blockchain hashes.
  - `flask_cors`: For enabling cross-origin resource sharing.
### Blockchain
- [Solidity](https://soliditylang.org/): For developing smart contracts.
- [Web3.js](https://web3js.readthedocs.io/): For interacting with the blockchain.
- [Ganache](https://trufflesuite.com/ganache/): For testing in a local blockchain environment.
- [MetaMask](https://metamask.io/): For managing blockchain transactions.

## 📂 Project Structure
```
CertiChain-A-Blockchain-Based-Digital-Certificate-Authentication-System/
├── client             / # Frontend React application
├── api                / # Backend Express server
├── contracts          / # Solidity smart contracts
├── migrations         / # Truffle migration scripts
├── test               / # Smart contract tests
├── uploads            / # Uploaded certificate files
├── .gitignore
├── README.md
├── package.json
└── truffle-config.js
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hazleshine/BlockCred-Decentralized-Credential-Verification.git
   cd BlockCred-Decentralized-Credential-Verification
   ```
2. Install dependencies:
   - **Frontend:**
     ```bash
     cd frontend
     npm install
     ```
     - **Backend:**
     ```bash
     cd backend
     pip install -r requirements.txt
     ```
3. Set up the blockchain environment:
   - Install [Ganache](https://trufflesuite.com/ganache/) and create a local blockchain.
   - Deploy the smart contract using [Remix IDE](https://remix.ethereum.org/) and connect it with MetaMask.

4. Start the application:
   - **Frontend:**
     ```bash
     npm start
     ```
   - **Backend:**
     ```bash
     flask run
     ```

## Usage

1. Access the platform via the frontend application.

2. Use the **Template Uploader** to upload a custom certificate template.
![image](https://github.com/user-attachments/assets/fee143d1-d889-4dd6-861a-049d59c5211d)

3. Upload candidate data using the **CSV Uploader**.
![image](https://github.com/user-attachments/assets/9d960671-4ad0-4783-a27c-0ffa18059eb3)

4. Customize the template in the **Certificate Editor**, add information boxes, and test the layout.
![image](https://github.com/user-attachments/assets/1a702d39-67ed-441d-9d5b-373de64cac7b)

5. Click **Generate** to create certificates and store candidate data on the blockchain.

6. Verify certificate authenticity in the **Verify Certificate** section by scanning the QR code or entering the blockchain hash.
![image](https://github.com/user-attachments/assets/ed5adea0-946a-46aa-82f1-a36c2d2d357d)



### 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.


   
