This project proposes the design of a national interbank payment platform named BPDZ, inspired by the 
European SEPA and TARGET2 systems. The initiative aims to modernize financial transactions in Algeria, reduce 
reliance on cash, and energize the domestic economic market. Although Algeria has existing RTGS infrastructures, 
they remain insufficient for meeting the demands of a modern, integrated economy. 
The project seeks to position banks at the core of a structured, secure, and interoperable financial system. 
By adopting the ISO 20022 standard, the platform will align with international norms, making BPDZ a potential 
candidate for regional and global compatibility. 
Furthermore, the solution envisions the creation of a broader Algerian Payment Area (APA), a regional space 
inspired by SEPA but tailored for the Maghreb and African contexts. This report emphasizes the technological, 
economic, and geopolitical implications of the platform, offering a strategic vision for regional financial integration

The platform includes:

Account Management: Create and manage customer profiles, balances, and account identifiers.

Transfer Engine (ISO 20022): Payment initiation (pain.001), FI-to-FI credit transfers (pacs.008), status reporting (pacs.002), and structured remittance fields.

Security Layer: JWT authentication, role-based access control, and full validation of ISO fields.

Audit & Logging: End-to-end traceability using ISO references (MsgId, EndToEndId) with persistent transaction journaling.

REST API Architecture: Clean layering (Controller–Service–Repository) with ACID-compliant operations.


This platform serves as the foundation of a modern, extensible banking backend ready for future integration with SWIFT CBPR+, SEPA CT, and real-time payment networks.
