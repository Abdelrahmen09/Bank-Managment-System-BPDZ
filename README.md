This project is a secure digital banking platform built with Spring Boot, designed to manage customer accounts, balances, and internal money transfers. The system follows ISO 20022 standards for financial messaging, ensuring structured, interoperable, and future-proof payment workflows.

The platform includes:

Account Management: Create and manage customer profiles, balances, and account identifiers.

Transfer Engine (ISO 20022): Payment initiation (pain.001), FI-to-FI credit transfers (pacs.008), status reporting (pacs.002), and structured remittance fields.

Security Layer: JWT authentication, role-based access control, and full validation of ISO fields.

Audit & Logging: End-to-end traceability using ISO references (MsgId, EndToEndId) with persistent transaction journaling.

REST API Architecture: Clean layering (Controller–Service–Repository) with ACID-compliant operations.


This platform serves as the foundation of a modern, extensible banking backend ready for future integration with SWIFT CBPR+, SEPA CT, and real-time payment networks.
