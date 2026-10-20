
# OfflinePay — Offline Mesh Payment Simulator

OfflinePay is a full-stack educational project that simulates offline payment communication between virtual devices using encrypted payment instructions and gossip-based packet forwarding.

Built with Java, Spring Boot, and React, the project demonstrates how payment messages can travel through a simulated mesh network before reaching a settlement bridge.

> **Note:** OfflinePay is a simulation project. It does not transfer real money or perform actual offline UPI transactions.

## Tech Stack

| Layer | Technologies |
|-------|--------------|
| Backend | Java 17, Spring Boot 3.3.5 |
| Frontend | React 19, Vite, Tailwind CSS |
| Database | H2, Spring Data JPA |
| API | REST APIs |
| Security Concepts | Hybrid encryption, replay protection |
| Networking Concepts | Gossip-based packet forwarding |

## Key Features

- Simulated offline payment creation
- Encrypted payment instructions
- Gossip-based forwarding between virtual devices
- Bridge-based payment settlement simulation
- Duplicate packet detection and replay protection
- Transaction status tracking
- Account and balance management
- REST API integration between frontend and backend

## How OfflinePay Works

1. A sender creates a simulated payment instruction.
2. The application encrypts the payment payload.
3. Virtual devices forward the packet through a simulated mesh network.
4. A bridge receives the packet and processes settlement.
5. The transaction status is updated and displayed in the application.

## Application Modules

- **Dashboard:** Overview of the simulated payment system
- **Accounts:** View and manage demo accounts
- **Send Payment:** Create simulated payment instructions
- **Offline Mesh:** Explore virtual device forwarding
- **Transactions:** Track transaction history and status
- **Security:** Explore the security mechanisms used in the simulation

## Database

OfflinePay uses an H2 database with Spring Data JPA for account and transaction persistence.

The simulated mesh state is maintained in application memory.

## Project Status

**Under Development**

OfflinePay is being developed as a portfolio and learning project focused on Java full-stack development, distributed communication concepts, and secure message handling.

## Disclaimer

This application is intended for educational and demonstration purposes only. It is not a production payment system.

## Developer

**Sinku Singh**

[GitHub](https://github.com/sinku1999)
