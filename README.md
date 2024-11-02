# TelegramHub

**TelegramHub** is a decentralized service that allows users to securely store and retrieve encrypted data on the Avail blockchain through a user-friendly Telegram bot interface. Built with NestJS, this project integrates Lit Protocol for secure encryption and Polkadot.js for blockchain interactions, making it simple yet powerful for decentralized data management.

## Project Overview

**TelegramHub** enables secure interactions with the Avail blockchain directly from Telegram. Key features include:

- **Secure Data Submission**: Users can encrypt data with a public key and store it on the blockchain.
- **Data Retrieval and Decryption**: Users can retrieve stored data by providing a transaction hash and decrypt it using their private key.

### Technologies Used
- **NestJS**: For a modular, scalable backend structure.
- **Lit Protocol**: For secure data encryption, ensuring that data privacy is preserved.
- **Polkadot.js API**: For seamless communication with the Avail blockchain.

## Key Features

- **Blockchain-based Storage**: Data stored on the Avail blockchain ensures immutability and availability.
- **Data Encryption**: Lit Protocol provides public-key-based encryption, so only the rightful owner can decrypt stored data.
- **Intuitive Telegram Bot Interface**: Users interact with the system through a familiar interface without needing extensive technical knowledge.
- **Real-time Interaction**: Asynchronous handling of blockchain transactions ensures prompt responses within Telegram.

## How It’s Made

This project integrates several advanced technologies to handle secure data submission and retrieval on the blockchain through a Telegram bot interface:

### Backend Framework: NestJS
NestJS provides the core framework, chosen for its modularity, scalability, and TypeScript support. It allows for smooth integration with APIs and external services, enhancing the backend structure.

### Blockchain Integration: Avail & Polkadot.js API
Polkadot.js API is used for interactions with the Avail blockchain, enabling:
- **Data Submission**: Users can submit data securely on the Avail network.
- **Data Retrieval**: Users can retrieve data by referencing transaction hashes, ensuring secure and reliable access.

### Encryption and Decryption: Lit Protocol
Using Lit Protocol, data is encrypted before being stored and decrypted only by authorized users:
- **Encryption Flow**: Users provide a public key to encrypt data on the client side before submitting it.
- **Decryption Flow**: When retrieving data, users use their private key to decrypt the data after fetching it from the blockchain.

### Telegram Bot Integration: node-telegram-bot-api
The Telegram bot, created using `node-telegram-bot-api`, serves as the main interface for user interactions. Users can:
- **Submit Encrypted Data**: Securely submit data by providing a public key.
- **Retrieve and Decrypt Data**: Fetch data from the blockchain and decrypt it using their private key.

### Challenges & Solutions
Managing asynchronous blockchain transactions while maintaining real-time interaction through Telegram posed challenges. Transaction states, including errors and rejections, had to be promptly relayed back to users. Secure key management was implemented to handle sensitive data submission securely, with a strong focus on data privacy.

## Partner Technologies

- **Lit Protocol**: Used for secure encryption and decryption of data without exposing private keys.
- **Avail Protocol**: Provides decentralized, tamper-proof data storage, ensuring the integrity and availability of user information.

These technologies together ensure that **TelegramHub** offers a secure, decentralized data management solution through an intuitive Telegram interface.

## Getting Started

### Project Setup

To set up the project locally:

```bash
$ npm install
```

### Running the Project

#### Development Mode
To start the development server with hot-reload:

```bash
$ npm run start:dev
```

#### Production Mode
To run the project in production mode:

```bash
$ npm run start:prod
```

### Running Tests

- **Unit Tests**:

  ```bash
  $ npm run test
  ```

- **End-to-End Tests**:

  ```bash
  $ npm run test:e2e
  ```

- **Test Coverage**:

  ```bash
  $ npm run test:cov
  ```

## Resources

Explore these resources to learn more about NestJS and its ecosystem:

- **[NestJS Documentation](https://docs.nestjs.com/)**: Comprehensive documentation on NestJS.
- **NestJS Devtools**: For real-time application visualization and debugging.
- **Discord Support**: Get support from the NestJS community on [Discord](https://discord.com/invite/nestjs).
- **Official Video Courses**: Hands-on learning with the official NestJS video series.

## Contributing

**TelegramHub** is an open-source project licensed under the MIT License. Contributions, feedback, and support are welcome. You can also support the project through sponsorship.

### Stay in Touch

- **NestJS Website**: [https://nestjs.com](https://nestjs.com)
- **Twitter**: Follow [@nestframework](https://twitter.com/nestframework) for the latest updates.


Built by Harsh Agrawal
Follow me on -
Github: (https://github.com/harshagrawal2503)
Instagram: (https://instagram.com/harshagrawal.in)